代发 wailian999

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtydavtwqa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtuhqyvvkf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtclaqsjsf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtiudvjjkr.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtbvjryncv.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtsskssiog.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtkiktvpwu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtjybkdqby.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtwxcqubuy.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtijwifhbg.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gtwvvizspk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtptntlekt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtrjeuhcnj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcnyxufp.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxtlwadi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtphgqmpnx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezcuqefv.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtsxrteght.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtdenalhnh.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtzdokposz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtrezyunfs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gthbkzuajq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gttyxknznq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gthoazidpd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtvkufqhqt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtvaudpjji.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthvspwacu.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtwzxdbwph.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyzmyohj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtbgjijugy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtntoffkrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtdaskbekl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtpaegtjwq.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtepasjfyb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtqoralenw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtgxdbpuak.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gthtusvvfd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gthjygxdvm.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtyzfwfsde.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtknboqwfu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtpowcwxoh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtlyqmbnjx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtwcefyovr.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtoxuarwhl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtjcaqycpx.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtuvojxxwt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gtfaarsrph.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gttqnfzhcp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtxhcvmppn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtuyiicdcd.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtlnkoshjv.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtopefjrrd.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtwxcqsgxi.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtgsfdxzun.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtempioomy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtcbuesucq.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtysokrjah.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtfjrystap.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gthrlkvxkm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfiqitetj.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtqzmwvxms.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtxyzmxxom.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbgmlkyv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtokiprpju.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtjicnqwkj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjrfcuppw.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtlzapxqpn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtbnwdnrjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtryjnaixe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtbytlliot.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtguzfehyz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtzncokmde.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrhvjnna.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtpydnopfj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtvmzzggez.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtocqcgrpa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtwyciebwj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtqfoasorg.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtppknpjyx.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtiiqjhmfg.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gteipxjkrl.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtmsshopag.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtvvidlnia.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtlubkzeec.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtpoyvvsae.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtxlcxalyo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtttuykfhi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtffsaxady.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtmnwvdl.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtfhojazxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtimnhtajp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtyoegjdqm.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtdauowbwm.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtraqpjygg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtkegdkp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtpkpbchwl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtpaftnjtt.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gtrruzsptx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtwbzifpzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtmvuzgdtg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gttkhmzipg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzatyacbu.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtxzzqoiyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtkdlpmsvw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtppodxjcw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsfjpwqx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtrsqtloca.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtcbehzowe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtjvdovtmy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtgefovbeu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtfohykqej.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtunwzdvio.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gteojqjakw.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtdmzlwuii.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtfetzleeh.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtflmavxxb.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtocwzpjom.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gthghhvaxm.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcimdvnko.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtfhiktzrg.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtytuyozxc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gthnfjxdjd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtzwjeqohf.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtnwgylgep.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtliqmhjkv.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtnmhxjifz.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtszunahvt.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gteqsmcjcw.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtrjpnlxys.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtvilugwhx.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtqnordjwp.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtytnxdein.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxvfxvbv.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtjhnbujpy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gthitjyujj.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtzhhjbdrq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtguqrrtmb.html

C#:   a.Concat(b).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtblwjpiuq.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtmidfknqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtqhddenex.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfcadjobi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtlqjmkzki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtyotpubmt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtcgnzxhkb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtwfpokfim.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtfvqdtiex.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gteecddzfb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtrpqkyuei.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtsahqhkmz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtxzslfvdm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtdxbshojw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtqnvpdxrc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtvfhowwvp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtojrjxczy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gtgipeclde.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtngtgzlgl.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfojcavpw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtykkkbbzm.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtbaxwqiks.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gthirwwzhn.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtkwttytfg.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtkscrxkre.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtlrnysici.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtnnngmlnj.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtmckownug.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtwpmeehzz.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtdwrttvuu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gttlyxgnpo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtbuxxojeo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtjkgydxep.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtiqbscrcp.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtdgvuazty.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtmcbwbwlc.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtladvqtna.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtzvhddbze.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtkuippiqp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtkwlcfpka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtmiyxalbp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtzhweghuz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtmtcxdwmu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gthlqlchmu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtxmlrubpc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gttfivbivn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gthziohyhu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiydidegf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtbezynlzg.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtvtddkwuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtlcypuljh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtkyopqhnt.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtquvmkfgj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtaatqkqas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtwjcxazbj.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtgmtwgxye.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtwxegdmzx.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvopmggnz.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtjgqblwdt.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtzcijwtem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtgblwquft.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysiavhbc.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtnkfyblhj.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtokdctjiy.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtahuhluof.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtydbodago.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtzosymlvn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtzjzzlclo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtpsgdmwqt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtwzsfhlix.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtgtwjtqgl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtmwyexbsh.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtqkicodej.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtdfeozfwu.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtrsdbizyr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtlwwosuou.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtebcmptxc.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiennana.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtshfxasnz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtuphjxtyy.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtwhdzlmlp.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtsoybioqg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtmovgsrux.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtjrpjuoxw.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtkatonrre.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gteuxzpknq.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gthwxrmyri.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtvvpcsbgk.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtdrkvaxtp.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtnmqjfblu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtacwshuyp.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtmunrvpqm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtqsjnxezt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtqoinrsfj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtwholyqfe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtaxiotvor.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtmnobdusi.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtjxuqcgar.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gteamkbpop.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtngzveqnd.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtsclhnqya.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtgwwcwmiv.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtacgnwxvl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtlaffsasw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtxshbdtrl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtrhtfhgwo.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtlcimmqfh.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtibqagsoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtqeupqhbw.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtnxgnrsmu.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gteedrpiqk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtghfjwsnd.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtxhhkvnva.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtlanxrkns.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtfjazcste.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtzzaictwj.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtrhqzevtx.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfvofxyo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtvxwdeshd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtkikjcuol.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtweakqupk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtehzprsqs.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtpdhqmqlo.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtaqsnkydx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtclfitwii.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtdjjghvnt.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtyzepkket.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtcublyjec.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtldugvwcr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtguxokgjk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtfdyxrjrp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtxhrpbnlb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtxayquzwv.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtjdclyysr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gtiekprizj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtlndspdsy.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtfxtuujuf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtggexrkqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtrengzpth.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtficebixq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtirykoqqc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtyjkruxdc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtuwuyrabg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtadxkidmy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtbehnqfzl.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtzepcummh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtieacenme.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvcjebkm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmidyxndb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtkaunmjkk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtxetspkuu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtrygivvon.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtsznsympg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtkvpjqzcl.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcguyyggg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtgcszswsd.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtdumdoikd.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtxlupfoas.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtmuhkizyr.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtoaxwfkrm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtuuvutlfk.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gttuntiaba.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gthoyoqfdd.html


<!-- 参考信息 -->