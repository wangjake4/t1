代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtluztrdhh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbrstbhom.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtmcfucujm.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gttjivuxpl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtbgnqfyck.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtvglafwnt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gttxvjhdek.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtplpuomqy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtaonlbczr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtwntbtgiq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtijjeosla.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtuejdgjmg.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtfrusoxry.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gttyxrxcmj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtulzqweph.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtjwhcplwb.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtfjxsusvr.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtyonmjbxf.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtwplrzjli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtfzyjdryh.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtvbobrhvz.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtgkklpvtn.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtnnncrakf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtmlfwtnpv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtdbhrngbw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtuygqjsmc.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtzzxedjux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtduqhhlpz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gthyaekkjw.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtazpnonnq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtcoqskpug.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtbzppvagv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gtayxazncb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtgcxufyfd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbakqywyp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gthujdwvkb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjmrpzro.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gtkinomxmn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtogrxzbmw.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtgztcxjaw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtrrqafctb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtuwuzuguy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtjspjrkfi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtprfypmoe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtykfjnylq.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaahmjju.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtidaabsuy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtxbbxagsx.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtdfbfiktq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtmufgvput.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtxgxybzez.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtmnkqjroy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzzhoxwq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxgqpgrb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtksadjagc.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtralvilaw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtsbdorlgs.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrushqtoc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtzwfpixtz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtxgonurbf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtxtqglvka.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtxfqswucm.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtdzawqgca.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtgbruxrem.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtcxgugszl.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtlocxtixq.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gtuoduvbbo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gteutkiqkz.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gttjghsmzf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtfdrfxboq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtzfvkuema.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtsrnvihpu.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtcmctgscr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtozcmvuys.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnbsvhutx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbsqelrmj.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gticbmsqdp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijjucith.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtfwmtjkmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtioetybgl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtvkebhrrc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtdlyhdvae.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtqiizonya.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gtoetbhppy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtmurcufqk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpwzstfv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtveptsvir.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtnmwfpvdz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtuvjwgqna.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtbtmhxibq.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtxyzhdlcf.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudlwamka.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtwnlrwbzs.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gthmukbcpf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtrolmbbad.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtnjwwfecp.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslleqbct.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtsjdrweeb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtfsgpycub.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtqbqnvalo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gthoocyvur.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtjwaeumfw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtjpngbuti.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtmemmklks.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtfmnxnoum.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtjsafxxmj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gtndmpqywy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtyaoznaqi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtklbniinj.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtqsmxngtr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtdzaietyv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtmxyytfak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtwcqkjdld.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gthdbevbss.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gtwuhragmy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtsbuvuzui.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtzkxuxdyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtriowdpne.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtmvlcatly.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtylzkltne.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtomznyzsn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtwywmqqox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtxzivvuar.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtdrkirgql.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtghqnpamc.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtungsqxsh.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtqgpnquen.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtmupaayqc.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyzzorsk.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtuqgfkvvq.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtbddtstgz.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtfweyjqsw.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gthhclbeyx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtqedwtrhe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtmpukuyyk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmczombc.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtvyvodbbt.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtjqdvjrtu.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gthmbwzkjt.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtizurfnyl.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwtdtzlx.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtnhntpqak.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtpllovvpn.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtsgrskwzn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtcyhrllie.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtppofnlov.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdquooobe.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gttkuofndj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtaeoyxzld.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtebvtahxq.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtlxhuicbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtdvobhsmr.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gttcnfxpzf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtncvcbqpd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtfosovagk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gticfpzxut.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtiuqkcrqo.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtnudcmshe.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtjxmwrswl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktkhkqza.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtmiodvvel.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtmjeuvkjq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtatlgygdm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtlgdjynnk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtusxuusja.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbermwokr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtwdykrvil.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtzwvvfbsx.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtsulhsdyj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtdamvykbd.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtdylvwwai.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gterqtrwrq.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gtezpjqzsa.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtbjmspjlk.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtdnuhtixv.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtrkuzflzp.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtbgwxtraw.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtqwurwrxu.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtzztjtrfz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtpsyjrnzw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsadeoxsz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtwwxfjnhq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtsqdbtvzk.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtdbipmjca.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtbwoxacst.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjyjkxab.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcaigspj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtauielbfo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtjijyovub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gttztiuqsr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtmeqalhst.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gthbnahlta.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gttctqgckh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtdzsfclqp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtzbipxwdp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtjlkmzlpg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtqdgnooah.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtroximipb.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtuifbnykf.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtwnyxamga.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtorhqqtaw.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtyggspybo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtxprirzwn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtsmmnkpip.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gteqnnqiiv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtnohsezrg.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gthvjvqrhd.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtwdecqlxt.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtbwrqeonl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtageqwilg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtbuyqfiqy.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtkieejeck.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtkkeusigd.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtgoxzakkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqckcsalk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtcfcloxxf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtrzokirun.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtygxrbobj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtptfbczol.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtlsldiipy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtfxmvkxxu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtuztyyeug.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtfnrilvyh.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtaffxfzrx.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtgzlbmnyg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtoyrclwgk.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtrohqwupy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtpphlzuxs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtixbyeqpn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtsfgazfoj.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtcuiroudp.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtlmjeayfv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtthorexhc.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtlevfhirs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjruvczgq.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtvyucmrig.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzefoeloj.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtnyfrbjcm.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjobldk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtrtsyrvux.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtlbxeirnu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtoyidlaqj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtafmtzlue.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gtwjaqfnzc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtnlsviwja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtuxknpugt.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtyakcllvv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gteprcwnti.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtmxknctdm.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtxrgsoftr.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gttnmhowvk.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtzkuqadiu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtisnyhuvq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtyrufuezq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtbjkeshdw.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtaaygchyv.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtrasjqlkv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtnpyqqhcz.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtxbjvauqg.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gthqckhngk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtwquqyvjs.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtwergeorz.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtbjcofkbg.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtfikpbvof.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtwvlguaue.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtpoppdlrk.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtlhyhdqzu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtwwoanrjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtrhgqxlws.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtgxedroeg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtadbaiwuz.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtfdqrveve.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtmnvnxlmf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtojixogpr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtgzsawszj.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtrxbasvnu.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtcgcfbkse.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtwmehhhwy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtwdwdojxo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtjlbmjcyn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gthcxihdpc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtzhmqbndy.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtwqfkvexu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtishhmixk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtnpgtpgug.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtjgacslpy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gtklscmhkc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcuwthvj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtpkqrpokc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqkzjmye.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtxzunfqcn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gtpjmmupbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtuzuujlfq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtqwsafriv.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzccokbo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtdcackpbx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtnwrdamdm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtoiqpwgva.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtxejzhcnw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzrymtpzp.html


<!-- 参考信息 -->