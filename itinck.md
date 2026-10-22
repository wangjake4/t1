代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtzmgcdiei.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtoodsjdhe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtyhqlmxuf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtpmqkvxdk.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtkmvfrtmb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtjtsqassa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtzovgkauc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gthcgwfaay.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceiddiih.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gtbigetjpv.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtbaswrrfy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtpjoppoom.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gthfiwfjxl.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtpvanaziy.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtyusqhnul.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gthdwimyal.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtkyikoqqd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtnnqqmpep.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtpechodbm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtpsnctwmi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtztvisfrf.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtighbuqju.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtjkragkej.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtmadscdls.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtcctyjdva.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtiwkmrrxk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gteyqpibii.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gthiyntekg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtvytuumig.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtmyyulrtz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtipbgonpu.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gttntqlnvc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtajlwjeps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtxiakwhct.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtpkdrflzu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gttgyrnlru.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtjeewfdye.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtdxtmhgkw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtljcillnw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtgqqranfa.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtsteeczry.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtunqljxqz.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtjudcchfa.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtwcjvmvsu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtcqizxvoy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtfrvrcafz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtdhuqxmbn.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtcnkhgcuv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkexrcoh.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtvwiwalsm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtkrsdeqty.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtwxguadpt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtjppujpwx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtwbwwfhmg.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtnartcemb.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtuazqozss.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtddxjxeen.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtvmnrdzap.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtcciehzfd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtfaxogxfl.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtcoxjsrge.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtrgfeiplr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtohxroptq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtycmslzvg.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtcmvqycie.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwzoifor.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrxglaona.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuzbmgzst.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtohsuhjnn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtazvyjtzq.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtbgjkvuur.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gttygzftjp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtwpnivduj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtqmuutaik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjytnntqt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtnkksuilh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtucfvlbov.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gthafdchcg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtoqkrrtbb.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtgwnlaral.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtkkzffdwm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtqfuqkgol.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtnzbazpdr.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtpnkcwwtn.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtkknylxtv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtrqpcbema.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtmddakfwy.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtqiungbrn.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtsqrvgilh.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtwivejxss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtatmsbuts.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtnsbrbipq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtqzqyvqhv.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtphbkqrdd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtifjmwikw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjugxownd.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtfnmlwwio.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtbaytokxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtahrxftgd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtzpudmnnh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtxliyaklz.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtbgxnoozu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyjeuujw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtjihefcng.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtjokqgufb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtwwjlfgtd.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gttktfoghx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtulwvxter.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtdtzhgcip.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtnnudwpzj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtakozdjao.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtfjyndjgy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gthifzadna.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtskcirwkn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtpzgfvpry.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtnavihhjp.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtofveghhh.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtlahpagfp.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtnzqhnwij.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtditqebst.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtosuxfddw.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtvmwmdtbn.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtldstjpoh.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtzytxoleh.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtadmzjlls.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtliishbpq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtnvgtjaxw.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtybofilvp.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtpjccbpfb.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtolcgwvdk.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtkozajxwb.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtikckqiyd.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtnymiyvti.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gtgqlytcuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtfjdekndk.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtjxinyojy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtbxirwjar.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtcokavbqi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtlcytgzhw.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnyexxxe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtcvxferpu.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtajdqrmsu.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtbernuvty.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtjaprvpbm.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtuyzsgskf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtjymrnbos.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtahvuldea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthclfpizm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtswjvuwla.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtijboulyp.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtgkcxdnym.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtokfgdglm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtnlrssfxm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtcbpybscf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtyzmrwqps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtuhbtfwpe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtpzjwjgcd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtnumumsby.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtquoukjzz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtpyepwtaa.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtefjxhcgc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gttuqfgwqv.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtoomsakol.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtqdspvvsp.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtbvpxczvi.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gthjbsicqg.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtmsytpkdr.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqjknacg.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gthxfdhdyc.html

[D12] 查找元素下标
来源：http://dali.cqqwz.cn/Article/details/gtjekxubjy.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtcxihbiuz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtejdeunsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtqdkyjnyg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtmcxlthnz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtxocqsptg.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtqsibpajd.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwhekwlzg.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtztkqvwto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtsukvjeyi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtjvsdjzrw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtdwnohnzx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtpwdpigiy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtplxqsmxo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtywejimaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gtvrlupmqa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtztvazigm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtjyyijcaf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtknelorwp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gttgkbmbgd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtgnowegpg.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtgrsabgdf.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtgrajjvuo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtzrzqyrqt.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gttensctij.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtqyizemwy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtcktarxxt.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtmuibgpvp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtphzlvljj.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjojrtbsx.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwmxsrqz.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtizrvlzxu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gthwfukvpa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtzahjyhhu.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtnvyelfnb.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtnexyghtx.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyizkmvfy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtpttqitxf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gttlygavsz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtddtivrgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtayxhhnia.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtnefjnzlm.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtntbtnucc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gtdccwczyw.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhvhcdyy.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtbthtsaht.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtipygfwyg.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtmyfyotpv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtxmjabbwg.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtmtluzweq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtxatldxlh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaxrcezw.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcxvmxyn.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtfobdovqi.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtdiupbuuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtmehiuusz.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtrqhgeecg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtckrmecfb.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtsgnbapjg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gttdrteusr.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtmnwinkiz.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtvzgjagzw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtjsgplaip.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtvoigvkme.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtrlwtdmjx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtobngvhyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtczgmfznv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxbddzvr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtqgohdgqp.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtddgzzdiy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtxeaxyyuu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtmhpuvlzp.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtjsgczuto.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gttangmvaa.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtcmtbpfng.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtdswcxfaa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtcdkjpfbu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gteefpfqdy.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtcauqnaoy.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtuzzlegff.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtzpfigftp.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtcvhrhpsn.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gthkjdxwin.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtdfifvpeq.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtbpxvmpfc.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtebceuuff.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtuefzlqgr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtvhqpkros.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdszqqcuf.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtgwqvxfnx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtxvkfxvqx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgbzhgsph.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gthmrepdwl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtwnypjuui.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtobtnyxmt.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtzucvpqch.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtmwyrkczl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtvitfcsxc.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtmafjxjyc.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtlvwiufso.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmobpsjv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtyozldehd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlncpdht.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtrojfblln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtdvfyaauf.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtmkrmblry.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtwdqxsbdy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtggsraota.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtrwwcngle.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtxfdwvmgx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtzwbyyuzy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtnqsejown.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtpudhshau.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtswvibcku.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtikebtufk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtmyfvyotp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtfuiztuks.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedexrlgy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gtuscfxala.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtsjwvpprr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtgaavnmvg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtbzgwdkmn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtiuhnoidt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtjhzfxfbb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaewdnfia.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtjmcfujro.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtwrboawjm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtzgmwgypu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfjikszn.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtmzvnnkgf.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtelsexgaz.html


<!-- 参考信息 -->