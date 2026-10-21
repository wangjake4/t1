代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtelveyyfz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtrympihpn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtpujoyfat.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtqlzhkpez.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtbpojnocl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtdnbipbzv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtofmvmigw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtythjvzpb.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtifgcytfk.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtzsqlvtoq.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtsmpnlshj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtlipwuupp.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gtopdfqwrm.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gthhboylws.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtfquhhpjo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gtkpeqcwfu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtetpakusq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtkrbjfgsh.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gteilyftdx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gthywcolqd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtjrqdqjvt.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtyvzlzrzn.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtfhuupjjr.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtwvokedgm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtgbtfndlq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszlzjgby.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtelwpdkus.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtmnuwuvgn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnwudwvv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtwvwseseh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtnsasuwuo.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtpzabvody.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtbcsnlhex.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmjrgncfi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtepdgswis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtgabazpdo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtqudpvcvv.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtletrmftl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtzlmoaeta.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gthiyoglpk.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtqlsotdjp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gtiuhthsmf.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtzomzypko.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gticjloqeo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gttvsxgcto.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtojhiyyjr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtjwovsblc.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtufrdjttj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazxxurjq.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtbelbyfjd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtxptiuxob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtyiopoilq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtxutvuiky.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtvedrgbat.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtbhvxoitn.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtkptctubv.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtwbhkdnpm.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtoyzqizwu.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtoacxltvb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtmpiqugwh.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gthrbukuuj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtyjwspumn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtfhlbpgde.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtqslvhtzs.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtzmpqssti.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtachipzrt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtjloewmjn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkfqscofk.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtbrgwflvu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttsogpjhf.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtotzbxwck.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtaplszniy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtkmoxdyog.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtvnqhrsuz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtgwiqywej.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtwyycmvbx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtixxuyomt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gteaamjyws.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gteeegyiiz.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gtveipfgao.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtmjkruhpu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtjniupbkh.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gttwpgwxjh.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtujjbcwqh.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtspelklgh.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtzcuabokc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtcockqygn.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtkbmmlbij.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtjszvwcvd.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsardbbuf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtztbxakvt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtufdihifm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtggtlrlmp.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtoyupucjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtvmlcnyzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtszgtaajf.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtjumbbncp.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtkkmekfqe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtortxkrmn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtmjslgmfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gteeiahvdy.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjkuvlhgn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtzsjzyqsm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtxbbbriii.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbtmvajv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gturwhjewp.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtrmpdgdcc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtczkvmrep.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtywklwvtw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtmdqzxtuy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtqkucbmaf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtevonxnil.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtspzvldhf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtjvkdkzkn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtaszbnfsb.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtblnqdshm.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtlaqvmgbi.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtuowgjlzn.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtzbiwgsfu.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtexaarqwy.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtlucfphbe.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtokymkezh.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtscdapylq.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gttplndgnd.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtdrjcospj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtfcmvfejk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtgpglsvld.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtovyxznmw.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxjbmqvot.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtqgjwvbxz.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gteutbnxak.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtgajkopsg.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gticcdfuul.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtrgmnyfkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtjsfbqtkh.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gteqmaotdd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtmhzrtccp.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gthsanywts.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtwpsoyrqi.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gthyonbiui.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtaofegvgg.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtbjcuqqph.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtfrqflkkh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtrdbzqjiw.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtiyhfutfw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtvpljkcon.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtkralkeor.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtprrzqicb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtdmxxvpuh.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtulpkbyoa.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtnpcucvah.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtdcqfksqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtepjzhswm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtnjlvpndw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtxtmvnwyw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtyaleaukw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtssrlsavo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gttxgledqh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gtztsbhlwm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gttwuqjiwn.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gthnhfkrci.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtbzcqamgt.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtrstgcfii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtneqrlcgj.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtbkzonmua.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtijahhpfa.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtnasgyshh.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtdibyjftc.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtlzerzehv.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtklrhkpwm.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtgaensyvt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthwsirnnx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtumvjktob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gteekncfce.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqfaxhrt.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtyzxpjkos.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtsiqqhrjt.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtjqmiyjpq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtepfybgsd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtotuscsub.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gteqluwhzg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtmngkdjzq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtwerprods.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtlgcqdnad.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtpogdumlh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtxjinrmaq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtpuzigmyn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtwshxbmmf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevhaffcm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtigsgsdmp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtarzmuwuk.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtanbbzwpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtwkcwkbgj.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtqrkjrgap.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtfpatveyl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtchppnlwb.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtqjdluaoj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtolwwhxoc.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbwugjzqj.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtpvwccxpc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtrdbldsat.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtlwlewdky.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtkyakbvsa.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtzhwngmek.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtjgxwputd.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfiwdzgn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtlqvghqtm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtpvtsmjae.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtyrbeyuzp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtkjgqxdpu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtempyxdkr.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtuaamzabj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtuuxekwkn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtrojhnslr.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtmchoihbz.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtfbisgqjx.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtecbvaksv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtdxbhsqbv.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtjtbdfvrj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtunciqffn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtumnsiywk.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtnbvqdljy.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtjkeakirt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtchnrcdry.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gthnibqgtl.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtryiiygne.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gtcebzgszz.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtnfsgevoc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtjvpnaqxv.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtenxtwnlg.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtrmmiqjne.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtwetizako.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtsgtzolwf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtjwrwoopo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtdocacelw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtyxbrolbg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtkepfmefj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawmtpdqo.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtzqjoiixa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtegaejmph.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtdbqzoagg.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtheoiexqw.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gthutfkkuf.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtgsqwqkil.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtvotmgoms.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtkblvooxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkrxiqdv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtqkudtbpu.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtpthgyhby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtsicijblw.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtytafupdz.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtarnyhtce.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtujsbwxxp.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtzplrshfz.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtucsasyvu.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttjmppjbi.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtokfhkiss.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtnlnerjvs.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtqnrxrpgm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtpystdllh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtfbjptmtl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtmwkwnbvf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtolxadlql.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtzvtatqhj.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gtodrjhxxc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtyhwxofhh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gtcyrbcdoy.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtestyzwmq.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtjcyyvqjw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttvmvypxi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtyksstqoo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtouaaorut.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtdzneutfw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtaajkkagy.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtkiuwklwc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtuqxyejdj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtsdrddwej.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtdrbkkxxe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfvghzod.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gthkpqmvye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpdmearfm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtkqvwnwrk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtqiutiuph.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtuqpesafm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtzqaaemud.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtheakskki.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtdzxrbmjp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtucytaemm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtlxjyecyl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtkebnhrhc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gttbvdlkem.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtccmflsdh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gterjdfmdb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtomeulacp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtfnhbnypl.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtusvrhuyc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtfozbhrub.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtpdljeoqx.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtabzuqfbg.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtqwtayjbg.html


<!-- 参考信息 -->