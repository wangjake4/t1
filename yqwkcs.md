代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtlafcwsop.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtojkobbxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtuheukwcq.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtzuqjzohc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtbazdkcsy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtozyyvniu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtytgptgzd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtuwylsnlg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqpvvrpfo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtvobaspmw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmvtqdnb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtowgsyghg.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtfufvlagd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtuqxkitru.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtrjjkbjuw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtfetgyfwc.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gthwfvnvxo.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtxrwdmjch.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtcmmzjccu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtrzdzkvqh.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtyzluurui.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtdfxhfqub.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtztlmahbl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtlhysjvpr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtvzoolrrv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumiuzeim.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtjuhpwtjq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtrnflsjuh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtjqqxfxky.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtkdtyicnq.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtsgsosbbq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtrenthqat.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtancnccne.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtjbwcqubw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gthulisemc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtwvvftjas.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gtuphgfqyr.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtcygdqiwp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gtuvfbukdu.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtblxxissf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtdgvczder.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtahobpies.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtsgqzgnqc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpefgjb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpaawujjv.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtdwjnlple.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtikbidsaa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtmrtuwzoy.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtrbikcrlt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtxfhgubya.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhuvpcry.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagdueemr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtacpnekku.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtaesmilpp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtjyckpraa.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtosgnfutz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtarwweelp.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtnoylewkb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtjdcastcn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtbgkexdck.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtfbfgfuwo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtcgcvrqsm.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtagnopkrv.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtjdyyrsds.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtnlsbajeq.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtpedygvdu.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtxbswdayz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtmxempyum.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtiinzaxyz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtidlfjxst.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtivkzyjog.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbgksimhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtzqsmbnbr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtbodjyqdz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtaqwyftph.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuvjszebw.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gthhstcfmw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfiaagxho.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtnhjrydty.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtykejkbbd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtwjvseebl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtyvzunlkh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gtqwdzjqtz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlzkoglj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtwlztvynv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnbktbai.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtwwifggyu.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtktjwziyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtzdpbemni.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gthacuoisi.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtggnkplls.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtxnhmrkmq.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtvnbxuxrj.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtdogakmmd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbmswxjl.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtfxvgeaaq.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtsjfarhvk.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtusqsxhma.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgzsmdulo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtwzqhnpsn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtjucyioia.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtgizolfqr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtymfhhsaa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtlblpzdmv.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtszcszcly.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtocpgwfps.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtasymithd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtuzzyctkv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtfznzhakl.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtjisnpeau.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtfdhuehus.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtisvercpa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gthjzlfqpq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtsvjseivo.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtpzeiipfc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtmurkwvqt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtrnghzpmn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtkpwcegvg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtvkasrvdj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtvezemnox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtsemaljok.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtowzyvyrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtqcnthlks.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtwqotiswb.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtakmaiutu.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtggdhyjms.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtxojdouey.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtuqbdxoik.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtolpvliww.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtshxoxmrm.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtxzhscvzk.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtahcvddju.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtglznbrtf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtyympumkx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtgzihvteq.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gteswzqymy.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtitrcfgzv.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtjqfvsbfi.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtstnepmee.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtlfgmxjhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtjddsozlb.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtuzjtwuvn.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtigusbzun.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtyxusddct.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtxtyjduiz.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtvxawttek.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtzntzmejs.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtoabkpgwa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtlabwolda.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtrcspjvmk.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyxleunm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtgqwutldk.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbkahdukz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtyjusfymu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtgxoiqati.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtnvhzkfod.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzfzxwbq.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtlfecflfo.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gthczijvyp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gtzjrzafif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtrkfzpxmc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtpwnenjmm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtrasakzot.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtlenilnpl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtzdcrvmda.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtfwndjgcc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtzvkbgvbt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtvysysruh.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtrabzylav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtylacwblm.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtowswmlnu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtelbhpgzu.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gthsgxztax.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtrmzzfqzo.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpekruexi.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywdlyveg.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtlhhzlhde.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtpqffrpxs.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtbkzznprb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtuhuavcry.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbrkxttf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtvnxklfoc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtlqekhijb.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtkxttjcnq.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtscozvsra.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtmcsutjjr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtabfkseyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gthqffgiyf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gteeyevlgw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gthqdxamzm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzarmpjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtggzsqbqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtrizpwfyj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtwysysuon.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtnxmssouh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtlwkhfnwa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtgftpsuvi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtrdvpehde.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtynauzfmw.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzrbhqc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtpuiwaavr.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtxxeqmjbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtcwfbaeby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtggkvpudd.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gtywqnciaf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtnmqrlcjg.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtpndvcrib.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtkiyvxuch.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtfjvsycdj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtvzwnltqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdogfwyja.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtofyxkups.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtumfoiwne.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtvieuvwyt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtwqbxsyer.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtfapbdyzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtoypusuny.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtflmueget.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtytfmbvmr.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtumtkkrkh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtbkypvydm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtuhbozisj.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtilaytnou.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwentpyst.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtqdfokuen.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmruelafh.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtimkuvcxw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtmcmwmwrw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtqphnvnjg.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkthxlzu.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtsgatpzjn.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtesamsbot.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gttyykohpg.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtccmuibdf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtydzicuax.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtckgrfcgq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtmrpznqjo.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gthldbehtz.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtllevccym.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtmblxcvhr.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gtzxugyglq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtcsagjrvg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtqmeodovj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtjgrdxpbn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtdjympapv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtmkxrguad.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtbdjytkre.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtnxywnava.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtfpsucxtu.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtwrbzwcsh.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnkblkgmb.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtemxppboz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gthkbomkvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtomlekgdh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtwzjmrrji.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtiepoxhlg.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtvtlrqnvy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbzdpsyg.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtbrucgxdg.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtwkkjnjso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtrkaheslu.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtkesylfiz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdinddkvp.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtvdmilrsr.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtweqwrglo.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtrndpglid.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gteyfchczd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtdwuvhoel.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtksbrsixj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtjhrmhfrc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gtvwxnfvzb.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gtawmpvtiu.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtnfwrqcfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtsfiahgfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gttdbkmifp.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gtctnjepmb.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtmzgmjhkc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtfioiwltg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtvdbqjtzz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtjbgymues.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtucosjvzq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtyqhzaydp.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtvgxtppzp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gthfaitogl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtyimfhwsx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtzzcngzwu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtvidtpani.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtbfybwhgb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmawvnye.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtclsssjgo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtdkmpgjoj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtzjycwyrn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtwassbppm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtjikbxkth.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtzuogkaok.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtipuupfke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtncciftmb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtosxxtmmp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqayhchb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtdjjjzjtq.html


<!-- 参考信息 -->