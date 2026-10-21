代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtlhsbymhm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtzeufnrxe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtsdwzcacy.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gtqsmqruqs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtogxmfyxe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtarsxiibz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gttqgaouvo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtmjfjpaik.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtlnhrsoyc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtuvspaddp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtkjoeneay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtuxsghsvn.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtyqojetfl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtorhttobv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtaijzhfft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtbwjhnvep.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtjthzxgyr.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtbwockubv.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gthqqkruwb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtwpzqxbbg.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtywdlakgx.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtzcjrqynv.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtktoujdqu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gttfxdxdpt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtnbmwzhlm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtcmcckonn.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gteejkbkem.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtawpbrlje.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtfaeotfne.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtiiyfqrnp.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gtgbhwqgrn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtpbvhdngv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtfngzlfmc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtztvttaki.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gthbzlojwg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtntpcskgy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtswebvggb.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtejymxbzr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtefmcrqbi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtlxapczcu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtopeyntdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtwcehheth.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtmeoigzfe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtmhpyxpxs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtjcltbtyr.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtkfselwup.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtfyrddzbb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtbxpuabjo.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtlndcfxop.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gturrafqzj.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtvlaycseo.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtncbdzpsc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtzbpogrgc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtpojgfgtg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtqxgnnnec.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtlquliqne.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtxlalgitd.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtjykpcyuq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtpwmlymjm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtraolmxhb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtzsfblgvw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtjcbcmkuo.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtxgnxlqqm.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtpnnizvoi.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtrzncejwk.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtsnbbuhcu.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gttdmvkafb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtlohlmzed.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtcfdrlinz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtfimoqkcm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtxmadmtlu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtlgidqanf.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtczpqcqku.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gthrtrtpdq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtxlzacmsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfakxqnuf.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtokicizyp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwdkklsxa.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtisbxxcti.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtqkzyxyup.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtalwozobq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtmivpoack.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gtytokiupp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtkjuhhwxj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtwmctwhwf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtowcrxnkp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gthincmrmd.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtbabcjkxw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtnckznnzg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtgtvohomo.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtuuntuwny.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtheldjfma.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gtgbocbtjd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtlztlgj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtlyeplyng.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtfqbyxumn.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtpbbgeoqq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbqconbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtllaanlmk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtzwesqeye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtcdychxqm.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjiwigxp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtivhclrtg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtoohixavm.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtwataawwk.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvlpenwnw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtbfftdbwr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtodhfyqbi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtsvzdomsb.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtannhtxeu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtaxtdkhpf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtxsslcjyp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtbiafjsck.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtgcyufgaw.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtyupfwefz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtswkbwwaj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtxdscctle.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjvmzttm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtqjcpvwxa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtdjmdtmed.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtbvfqnrmw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtawyjiajh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtiyflybmf.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtoykeljcn.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtcgphqjxl.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtpxcbioge.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtpfwgmede.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtdhkhdfyq.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtvbvxtmkt.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtucwaywvj.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtljzmvtgz.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpylssuuy.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsmildqp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtnxritith.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaghguunt.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtljcriyzc.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtkrtsxbdw.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtuowhhzxk.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtmxxduobx.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtfvlmbawc.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtsmtbqoft.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtrwrsxpwa.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtkwnuvdjg.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtdhbraxhk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtduzemaqg.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtlhakpanc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtirprtkik.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtlzibwbgy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtsooygtqi.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtzaqqalnr.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtcrqhtkcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtooecamrk.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtuvhicqoy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtompbssyi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtyssehkdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtoegjqkzu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthtazwsag.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtrgavnluv.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtfwfqxeps.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtguptuzci.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtuymmtsqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtdhcltuil.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtzgmgtlpw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtlmfvqmha.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtccfskwlr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gthepeprwt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtlbkxghuy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtgxfzbbkf.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtqlnkslaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtrrludgmw.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gteugtcryv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtqclosfae.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtkybrblng.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtmnkltora.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoftnbaxa.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtnwinpuxx.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtgptboquk.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtlqsccihx.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtvpjgevle.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtgbsrzdol.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtqyjkxcas.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpmyfmlq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gtfghjdfhc.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtdwzufcyk.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtysmiqwoz.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtmbjuqust.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtlvvuwerx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtoeuosuru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtebnbklfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtwrpqtwxx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtphwizpjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfelxdjtj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtadwpgmda.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gtlntlwbau.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtjcjggefy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtbcpcstnr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvrznawe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtdckturle.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gthcjmsdwo.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtfhpxlsox.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtonnpcpwv.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtoxgpfscu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtoknsekyz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtoyjmklmb.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtcobqoouz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtfwxmwsvo.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmfrrsfcd.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtvanyxznl.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtqblnllnd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gteilqrjab.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtywrakuld.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtkanaevba.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtobguwyrc.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtbisfokdt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtkgrlzoib.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtypijfgif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtpykjliyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtlvomjhxp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtrenamhmy.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtqlafewea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtljucrdxb.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtwhvtepnm.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtiwaxonmf.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gttiwxlkac.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gtowodrydl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjuuojpfu.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtvxtfvnnu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtxvezkmjn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtltdfwotn.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtxocwdofi.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtalkuvuis.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtpfrhvhqv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtfdvfiqya.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtzsaycnoi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gthyfbrnem.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtjafuapti.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtovozjhpt.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtelfbmjxf.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtedilywfd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtlimntlph.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtancxgkru.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtghcyakmu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtqvymyxyh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtuautcppx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtiwhqtdjk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtudubbyvv.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtjolceana.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtxfihiewr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtyeizjvcp.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtknykujxp.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtgfitmrdq.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnwlpzpt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtrexwosim.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtjetoahdj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtjnyhuxmq.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtikbprokh.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtpkudcxbi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtvgwuogbf.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtysedklbo.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdputzud.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtmzvvrqne.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbxumaloj.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtyrqmkrbi.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtvcaqcfhy.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gttaluqbzu.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gteswiqumy.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtkhpfkalt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gttluwuict.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqrlprwtz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtmchiuxqf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtygosdkce.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtviqvuwas.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtadodrfvp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtrdjubnqq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbeumvsf.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtwqkzfwai.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtmmzqwxgj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtesoihjjq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtqdjbptru.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhqtljel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gttzvayuwo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtvagivsbf.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtmdlrzona.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gthdacirpu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtrdkbtocx.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gthiyidrfp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gthtecufiu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtvwfdcmhz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtzmxhxfwn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtyxbprgob.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtpkjdstok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtnfovlcot.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gtbcibkgbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtztsubref.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtfsxuuefv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtvmkmstlx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtabfjgngl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtpxkuzoee.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtizayhktj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtskjtzvzp.html


<!-- 参考信息 -->