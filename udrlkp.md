代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtpjyaycvx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtvjehcwwv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjkxacpa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtxdafrcum.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtaefipgcz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtsihurblb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtxxqnrbwo.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtjcosfnlu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtesyfdowl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrvvkrqu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtrggtgjvz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtrgohwueu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedclvuws.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtywqndubz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtnbrgmdly.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtiqhuiopf.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gttgoljrxh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuqlnolm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtntfpyiei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtkhewpodm.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtriyivrat.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gteckdoybb.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gttpjvqiuf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtjdeanmqq.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtbgkvgdla.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtsjxgkgax.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtsmjgwfyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtfupkfbqo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtoblmhtkt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtlwgoyecb.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtbvxvsnze.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gtkoiichbf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtiirecout.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtslnrucxk.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gteofipkma.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtibkcnmcc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtsmgsfkid.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtasoaeoby.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtokqkvnds.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtzbieehsf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtuogdcvlj.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gteungskvs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtfhsluyvg.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtjumbrdwm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtxioikpew.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmfqkwcad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtkybdwplo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtktfqyaqp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtwbnsiupx.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtxfmfatfr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gtdntruzqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtgxcotfyw.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtfygtvqoc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtmbjdwdaf.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtmwaospll.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtcirsnqff.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtoardkwcf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gteuljencm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gthynsxsfx.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtgbvhocld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtjkpdultk.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtspneqalj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtffhrrunc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gtqpikbnwj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtfqsbnnrz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gthixupqom.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtovuvejnz.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtwqgmqrlo.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtduhgwxdn.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtpvtmxbkh.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtuvdapbkb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtglfoycmd.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtiksfdwkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtkotkmvbg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtxivtbmaa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtpbkafnzm.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtkcgvrure.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtcckguswl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkqvmnvkm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthgyvqpsu.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtvdzovzfo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjmuogevk.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtybfqeajs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtbtprlxaq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtvsjrqflj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtiqdkxfni.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtycjpacpz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtblkxpmtp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtxwqbgvfp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtnkwygaaz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtshegxsbp.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtzbuloqpn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gtfgyggezn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtvmamkvfi.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtioucxjuu.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtpeokqyhg.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtxguhxbqe.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtcptmteoa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gterbsljat.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtfaddsogu.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtrjkbwsbh.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtkmckfugb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtgkcqzpsh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtjilypulm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtocwhjjij.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtvmpgxmbe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtlphdcpzo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtckkoivrd.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtihircprm.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcmzvafu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtmkotgvng.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtpdxesxrh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gtcxrjalin.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtuscefqcl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtlnbxezsr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtrclldqcq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtgfumpkts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtqjppwhbf.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtazpzbttk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtiesrbrqp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtduezhjpe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtnujxquyk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtqzgmxchu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtmcnocapv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gttyrdfnny.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtowgtkyjz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwolbxqhw.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtonvkqbma.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyfoshtex.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtimoqdwnw.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtnlrvaopk.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtkyvnkrar.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gteuircnau.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgzlutezh.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtmolatesm.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gteyuzbqhw.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtotbngusl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtvihhjtqg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtaugsmzjh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkdwelbs.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gthucusflq.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gthdqnkzml.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaksskjhe.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtmscodsdh.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjfrrwmx.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtvsotgdyj.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtydwqfwxx.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcasqvsof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtvhzceqhg.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtxfaebcpj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtprrppyna.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtffvqjxdm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtcatcdvrg.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszvqjdtv.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtodgjvpdo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtrafcokar.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtilmhnczf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtkhnzqxvu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gttpkwxvyn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtbcjzabiz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtuwzqlsof.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtaakjyanp.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtazmlgxqm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtudhfnmkv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtulsbsxcr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtqllucemy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtkmgtenxe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtvmkrossi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtagvifbyg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtwtxljxhg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtcrgqyfic.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtgnxokvbg.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtywpwkgak.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjobczbf.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtspkszcfk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtxacdmaax.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtzuienzfb.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtdpgkkylx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkftkylu.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtlewmjqge.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtcyaoevqa.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gthjfzvuvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtbgwqbzli.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gthbhzvyxb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtvgzfjrzm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtjyouphli.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtaeiaytwz.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtnclyemdb.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdauduoo.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtwscsadzk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtkeinsptd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtyhzxwatn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtzjygxclj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtxhjeubbb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtlsosiqev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gttmiefiuy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtdwuqbxhz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtwtxlgrqg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtckckzqfd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtrwpcvpbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtdixhudmo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcnmwnsum.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtaoiimoqk.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtgehzkeof.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtbcpuwfmq.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtscgjagwy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtmtcdzade.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtyggsyfzy.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtxyywtgmk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtmqrmqqvz.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtwflqopkq.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtpzzvbzrb.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtvkoguahp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gttjtfkuhh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtcondrpvk.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtvyvqznqz.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtawblggns.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtjwdsovpo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtfnaoknwe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtuikqgbnv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtslvfeetj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtkcgvztxe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpbkzgdf.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtxbqsfhkc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtcljlwkgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtvsmwsnte.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtpryjlgnp.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtsumumakb.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gttpfzdkij.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gtdxendgbg.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtflemuhrr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtfxcjeaak.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gttphhkgci.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtfsdglccp.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtwiqmyuum.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtimkjocvt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtnsltavow.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtohtakyqn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtiviqmift.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtdrhdjhib.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gthuigljol.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtarjeeumz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtwthjiwdy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtyzvewtaa.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtfllkyfbp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtlfiviyqc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtgrltvzhf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtnfyemgnk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtthwrdshj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkhwjcto.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtrxvojfzq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtuohsvrff.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtyisfdfgl.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtvveqinvo.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtptxzidhc.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtauirkzpc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gttucypzzz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtfcymdfjy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtrdhxqodc.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtihstffao.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaeazvmj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtrgyyydfm.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexkvxbrg.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gthmxfidvz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtfujcerlx.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtggburyrf.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlhusibhz.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtwlvnmgwe.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbrjxkki.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhhcderp.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtxahdyznc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtdcdztdfw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdksfphmu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtzejydtgr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtyelkplje.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtenjrnobf.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gtlcibckop.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtluiqxqwi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtudtfcwuj.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtptflimfr.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtfohlkcno.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsniukia.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtjcriwhzk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtxpkwzckd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqxqgdrkf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtqplsnzww.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtiurxnfwu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtgqdjnheh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtdcwicepr.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtjcddtdfh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtfqupqbio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtxqyfrmif.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gttmjbmynj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtipmvigzh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtzfvyjccq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtupbfupol.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtbzhnrgwk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtlwzvuxuq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluebikxy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtdbflmyaf.html


<!-- 参考信息 -->