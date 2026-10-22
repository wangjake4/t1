代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtphjpxdfj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtjyknlcdm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtqzrnbgvc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtgbrtsvgt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtevhccxir.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gteomrxyxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gttoadrxjs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevgrvgix.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtltncrtnj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtlaiyzbwy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrozijvhn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtooqpfzbn.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtknyinrhj.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtycuspmkp.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtqjlnflzg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtmnjydrlr.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtppzvupsq.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtgktdceif.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtmhmvlexv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtdeskuvoi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtisgcwcgr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtehnyconm.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtbmnuydqy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtlqkbunid.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtleudgesq.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gtzprgpmva.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtspzynkck.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtcibeddgz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtodjrhinq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtwmrhbiww.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtsmzctncf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtzxytwsrv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtleibbzjy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gttrqkdeds.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtpvflagzl.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtumnyuftf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtrdiumfmo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtocqrlhks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtawjctbkx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtvhvcvjtx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtnsvinmmj.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtkshtkmpx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtixrwlyne.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtvojpmwoo.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtvpowystb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsmlvuym.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtfzkrbtkv.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gthlgosvvo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtdazolcpy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gthqkvswmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtjlszczej.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcntjdyxg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtakttivjt.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtuowglnzu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtyefcpeto.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtmnqnjpxw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtgeadtzoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtqizgqizy.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtkstqizfp.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtyfjoszgq.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtdgrsfwmn.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtoazeskqj.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtnenitiei.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gthqwdqezh.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gthpwhnkbt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gttwuarevi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gthnqvsnou.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtrgerxyeg.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtqyonogct.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtmzcnmbtm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtoroujpwo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthqqopsgz.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtmxxrpfnz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgpwexayt.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtqmljbgeh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtifeyymdq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtkinhnapa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtybqhkcaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtauwoyqsw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyplutcvn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtnvkwgedx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtbrxhbahh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtmchpcrny.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtalbvxmux.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfepkxez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtmqqdqxkc.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtnbzaanjd.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtwzqqdwbj.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtwuxyzdue.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtwxeolhql.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtqrguqxck.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtdyylvwrc.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtiobpkiuz.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtwifbfhqj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtaxizxlpw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtfdczmoep.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtywfipbrh.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtpfdlpouk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtsrfntkaz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtuocquhvn.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtmuqocpzp.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtbzqyrbef.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtjuehbgbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtnduksclm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtwylkkxiy.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtmiyznciw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtaliixahw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtrjninbgh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtjdeyujgw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtvpolkurt.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtbwuhdhzs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtrhyrfqzp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtodzwayil.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtnliiquiq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtojpseuyw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtaamrtzfp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtmaoqazgr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtiozfdfop.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpodoqeiw.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtadwscxvi.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnuglxmxu.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcclmhzto.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtrqqzobtl.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtlvwfyzma.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gtsrbdutxt.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmjzofeus.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtsbictiux.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtnyhrpdmh.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtuvwyrxpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtraqarssu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvrngwi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtpdwhdvbt.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtwiggukze.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsitnrnq.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtefpctynr.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtsmotjmpr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtpjpzmkdt.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvxwmsgs.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtogdtkmrl.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtvnuchwjf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtmczeezeo.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtjwmkwupj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtedmnfbrf.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtwpdssllv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtvgjprvwv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtwshgpmrq.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtoujumybp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gteciqderm.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtwinvetdr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtcoapuytv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtytwoknai.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtbybowyfj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwjcbmaos.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtaotwbysf.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtjvsqnflz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gthhbqvaeb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtuetaffil.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtanwcffim.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtuzyzflej.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtmsnynlfb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtkiojhbny.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtczeilgux.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gthdolupqc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gttiivjisb.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtjdghcyiw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtzzchyfst.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtimrloakc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtgtpsmjzn.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpewcyvm.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtnouhtpuw.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtzwolpito.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtmbnfgpxx.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtvrvhqddm.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtmxqyisqz.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtwsetleey.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtorcexwmc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtiuuvrqgj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtgfvzjwom.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtbqffkxtj.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtzegemlyr.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtwnheuzmi.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gthvastndt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtedxxndzc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gthzlfbmlv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtuqbkpbem.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtydvxgbjb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtyradogpg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gttlcjclkt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtlmxkosnb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtqtitguly.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gttomvtxrm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtepfcxmtx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtaywzwnjp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtkfxkmzad.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtiazwfdcg.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtdlelvwhd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphugolxj.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gteowbouww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtjeehsvfz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtakqkwnup.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtpcnurlrq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtezlziice.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtzjzkphlp.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgricswg.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtcgyugjdt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gttijwajkm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtfkqxwnvg.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuwbrpxu.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtmkixrqhj.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtpwdopuod.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtbmhmnbpg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtjzsigjhu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtzannmszh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtafwidbul.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtgtzajpvd.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtmdjifqsx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtplmkupci.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gthmdecvrm.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtvstgesnl.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtcvhdglys.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtmbhfcbda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtppubzwyv.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtyvuhsamr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjngenmxl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtjsziqeuv.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtltpetvjo.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtefpiawlq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtopbjdokz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtzzssnqvj.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtvfudmcag.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtlcbgzgrk.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroiqymmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtimvbgqdx.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtrxpvqvnf.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtjudhlztw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtpiztwfsx.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtzbkkduol.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtdmhlpfql.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gturuyqysc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gttwmmtqzo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtggefcmhk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gttbbfnvfg.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gthfsqgaxc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtyzaymkze.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtmomadqcv.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtorptpezs.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtplgigcac.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtnbrmigde.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gthaiagybf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtjbfotohw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtikkhxpye.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gttspiijia.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtlobjknlm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzbqwryn.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtqervtiaq.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtvoyrmjch.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxqokwqx.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gthkkbyddk.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtwsxalcqc.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtewttctwb.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtuonfplpd.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtwwlyvcxw.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gthfyhtwnz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtamtmscjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedfczhqq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtmmwyhpca.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyjricga.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gteshzgugn.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtvlyzofjq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtshegclvx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gtblejbirs.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtcrtbviin.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtuqgsbezv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtedtrordx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtbihadkya.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtcgiciyro.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtaevbupea.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gteacgahah.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtskbkgmjo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtxxewifao.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtvwbhlxph.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhfebav.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtpeclsqnw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnancvlao.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtaxyvqanw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtpuiqfesz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtujcyfjjd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtgtbznqvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtkwgdigko.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtjwzurtbq.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gtgqqbkpar.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvdxelry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtcoqjvvug.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtlartkutm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gthprabxih.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtuxbwczsj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtwoggvmre.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbckiasjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtmzwibzfh.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtgbxglafw.html


<!-- 参考信息 -->