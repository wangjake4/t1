代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtndzyhiey.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gttmjomquz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtqynmhoiz.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtlkvnxuek.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtiulhcjvi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzqipcvay.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtsnlqibjv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtauietdak.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtpxivsdig.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtblolixro.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gttqgdzhlg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtjugyghxr.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtskhpybhm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtbnvnhfhx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gtdlpwhmcj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtigcfegns.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtedqqujra.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gtqgubydpv.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoinboor.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtrzvkrbwb.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gtdtsyprlm.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtsdblpahk.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtowhiwreg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtpmrludzi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtflmqivwx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtsqyrkfur.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gtopscdiza.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtjzojwkkp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtmiddmgzm.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtcfoomefd.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtehaggyuz.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gttghjlobw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtoeedrwcp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtkfghyuyu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtvawttmha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtzjaegjhw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtvssajduw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtjohoocjs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtjrzveswq.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gthmakjnay.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtdwgrhyfy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtduamnboc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtigxrsktj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtaljlivzu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtchjleysh.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtmtogstbf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtsibtzuls.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtfvwjcyuf.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtjllrxvnr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtdzuvuqdh.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtcospjzgv.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtdogusvqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzjghdymh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsacrftpq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtkaktdwuo.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtdglrhssv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtyluxmhkd.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtesvnfjuk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gtunvskfbq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtczlshqzg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtbuyamooo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpluzarx.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtlukhxzop.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtmunthpzw.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtzslxxcbj.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gthyxkyvir.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtnrflyxij.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtjcwhvnte.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtobqwfcnc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtrulvykqy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtxmlmyjzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtzyphlliz.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtxtmlxxup.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvgrfyjb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtexokqoea.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtanpgxdku.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gthoxbfuqz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzxwrchiw.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gthgxsbkdq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtvuenckbx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gteehzxhqu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtkrrpmbui.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtqylgxhwd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtzfumzbba.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtxtznwrln.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtvvebhday.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gterrcqpnb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtoezjkhuo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtyjatfrgg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtgbtbtnzj.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtfinkwdod.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtbpvecuwy.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtjtcrbqvx.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtskiahaui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtircukygb.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtvhltuglh.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjrmdqpm.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhrgrqhl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtuldcmyvb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtclrdnqjk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtjcywhfjo.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtdehoiskn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtibwiflin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtqdcounpc.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtozvwptfi.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gthlrtfosj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtgiuvvafg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtlfbvvlvw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtfqanhvun.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtkjmsouzy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gtdzgpxjus.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtgwhmdrvr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtpmylgsqt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtmgkafrgk.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtzwhrwmrx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtxuwuligv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiezfxgph.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtjsbyfohu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gttwehsbga.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtogejeswg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gthnvvprjm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtjllgzqxz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtupjzxbql.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtaijpfwto.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtwnwlmvrb.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gttgfvdxbl.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtuifejhfh.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtehhfowox.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpujwfotm.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnadskti.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtkyszblyi.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtxdkqidpo.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gtgujlxzfu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtrxsylnkc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtlkssjmpw.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtdurwjkww.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtxybitomw.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtcftifiqm.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtcobojvrf.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtiumhnmhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtvqsohvez.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtlbgqmkro.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtlxsacdbe.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtevwjetnv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gtrctdwllr.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gtrpnbabkx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtcgumfpfo.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhytkqtr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtsfykhmkw.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gthakoxtkt.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtbvmuymes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtghvlrhbz.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gthlwrgkrz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtyriajrqr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtjbuwynbe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtocplfapa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtvfybjpta.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtvknpdays.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwaasysx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtiwfpnxiv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtvgbutibx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtlwomripw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtjwffrekf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtqizbzanj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtiqgbddth.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtrlmgcezj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtcpfhpskw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtnspmwyxh.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwtmzfj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtxncropsk.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmbdfzdje.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtkqwoctei.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtnvcstyzr.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtrhdfgdic.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtrhekbytg.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtiaclyfev.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gthzlxxnmc.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtdibcpljz.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtkhrvelxb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtyugvdhyn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtczgehhqi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtitvzyzrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gttfpvdsxx.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwgocpwkd.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtupihixqr.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtiyoneqxl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gthlyplpqs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfvaijmr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdivdzed.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtlxyrhdcn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtwrhtacqc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gttznogcsd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtstzxrfhf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtqibjinpj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtajmbybzg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtmwbxdbvx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtiganrtny.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtlbjwyann.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtqlwyaqvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtqkvglcia.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtecfhgrms.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gttihgyyef.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtyuqeqduq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtlfewhdis.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gterhgbcjx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtheduudtw.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtoncpmukb.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdfwfexq.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtouzzfppg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtfulfljjo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtllscvfex.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtzylihezq.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnmxmdrvx.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gttjbavhsn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgldkhqof.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtoypslqkz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtssjmwdcs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtihgqxeha.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtilaxljdd.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtajtzlfll.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtcliotfhu.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtjohtvkvj.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthazewpvp.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtwsnsnzvb.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtbjgqmndq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtefavntmy.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtokpbsvjq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtwxdbdhni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtcppphizt.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtscmfdzwn.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtwooxvtuk.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtgokrjxbv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyqgytks.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtjthoxeto.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gthfsyqypi.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtyjbgtdzl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtrsqvivmy.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvoxjaki.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtdczfmuxy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtgqqxqxii.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtgternbil.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtkkjzsepj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtecueljsg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtssbyxukv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtpyptdkkf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtilrwroao.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtkymhuocy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gttxaerxrt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtaveybvxq.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gttnuccqrr.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqlbnfbgk.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtinozccgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtyjaqixjw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtfszfmxks.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlrejqvi.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtscbtabqu.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtqywxkcwu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtewtagccm.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtvxptohhe.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gteyurmzyy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gteuhwkbyr.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtcmuglfrx.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gthkgcmloa.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtluuvuuvm.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtwwupmbvq.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfwcjilcv.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtrdnsxcbp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtpaoljpgr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtczokqexw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtuhxlcbvv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlnjerujl.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtsksfahit.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtyqcliszh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtflpqsioo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtatspgwix.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtcmhkywbo.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtsqqaiysy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtrejuzioz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtedotcqfn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtpmxlrrnm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtszippqce.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gttjyxzjvi.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtsqknybah.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gteokruidk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtlqbacveh.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtzqskmnlt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtppljfnfo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtatpwniaj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtggpwkyuw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtdzbsflfd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtpthzrlaz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtwfpijfnv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtriydpull.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtlzvqhpiy.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtxgwjmbsp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtsjnviaqo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtylypgrus.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtljjroowk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtytbwygfj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtkqmchere.html


<!-- 参考信息 -->