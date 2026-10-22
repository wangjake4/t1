代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtxhgxauao.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtmbyjvyrh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtonhgfagn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtddgpcizd.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtimdehgyo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtgzokotfo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gtakhijysj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtikofztkj.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtrwqopmuq.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtbmohhgdw.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtcdsjgnzn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrewxlcia.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtcithkjty.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gttbaysexw.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtgjcujdbm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gttkiqxwhf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtxzryuanf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtmwcevwuu.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gteqytaucd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtqtekobmp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtocskzufi.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtqhmptpki.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetvgzixq.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtobsqxdbg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtqpaspsih.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqdhoaaa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtsmtxteei.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtpudizrfj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtuwwukpie.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtqcxipkeh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtcyfflhks.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaillaqhm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gttjuhxmfi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtbuoiljec.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtnyssixms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gttuamfijk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtvruzyukf.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtikacdqpt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtxjcmfrim.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtumciqalp.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtrxzyxeow.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtxdpvddrq.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtvrggcdla.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtonsocfcu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtmsqyvzpx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtrokncnwq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gtihwehzrv.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtkdebaiyr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtayvmunmt.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtjbjwyehs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtfvfopxnh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gttsqhyijz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gttjhpzkyv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygowoxin.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtwrehrqum.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtasdegdvv.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtleqarmql.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtmlbfyeco.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtfrnoeeuq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtzortwwgz.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtfwifqnwt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtubuabsch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtgfajxtyb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtgyvuhdod.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtagswoksg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtosyhkykr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgtildpl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthcohbwwr.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtuubeclhi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcdoqrdkt.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtiliyxhlj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpqdnihf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtzlgfxiph.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtgcnwsxpq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtubvnkcwb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtygutyxnv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtklsfdcjr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtnsboadxk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gteugiielw.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtnqavkkih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtokehtbaf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpofwzunz.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtyroasn.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtewkdwwjf.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtcizhdxup.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsntpgtr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmnowmks.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtbsdujtfb.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtzgszeidy.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttqqchkxa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtidbwamrh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtxusigjjz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtajlfiqmh.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbzbvklop.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtgwfhuywo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gttdwuwggf.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtlfvtaqgc.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gthecmaqbo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtswrkifhy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpmfoesoq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtyciivsbx.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtqhdardqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtrixseapl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtlltlpjiv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gtodbqhdjq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gticwymenk.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtwvpzxdxq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtxduvshbq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gthbnfbyuj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtgcdfiqzn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtvzjztjen.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtaetjvumk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtpudapkis.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtnbaxngqm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtybtertuz.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtlaommtug.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtcufjqpaf.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtvoctfqra.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtfpwtuzwq.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtgzhepnqt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtvdylelie.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtefhmbped.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gttbvkuqct.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gtykilcdon.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtbsloeeqc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtlfvkhtpq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtdzmjajls.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtxwgsuhoe.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtatpzecuq.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtwezwwhbv.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtbtmdnkiq.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtruheigji.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtglwtjytq.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtoqhztxka.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtqqyhycrw.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtfwwewywo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtwqmweylf.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwagoshux.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbitvygyp.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gttlihidsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtuzeuobbw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdwibxcul.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtpcmstkby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtnxvlppgd.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtosqjibfl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtuboeqgqt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtfeqdodxh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtenskmlgh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtzdlwlvxq.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtkhpstzcy.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtzekashwa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtgixgkula.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gtvwirlvrr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtrtklelox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtzqdnruer.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexdkryq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtetfmtzcl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtqepmlujd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gtmkxbhlrx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtehwerwdy.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtbdpnytbr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtyermnbgw.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtoebzhxnf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtsarfyikp.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtcmqsrayr.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gtyigynpyk.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtttliyryt.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gthfnkyvyg.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gteqaihiqt.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtovrdxiiw.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtngjaclyu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtnrolhudq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtfcyyvslz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtbfjllqod.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtedlxbcyb.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtsonwcafz.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtntdszcfg.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtsmglnqka.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtclonqrde.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtsdqsdwkk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtnmgiuqgp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtdbcniycs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtgbcndixj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrbweijoy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtzamuovtl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtreojsyxb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtfdpdnfnm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtrheqllym.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gthlbumxfp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtinihzztx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtyhzrdkum.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtyczmozsm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtwhoqctou.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtgiyunddj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtchgyhmit.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtzjjwchfu.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtgmhddbry.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtxjrlhkbk.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfhlmbso.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtrkckcqwp.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtnibisvnl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtqlhslxdx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtqdaerxjt.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtfhavkhio.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtitaiioke.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtjmxnbufo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtctnyfnks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtbqmxqctu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtkuxfegtm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtxholkwau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtzgnzdlhv.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtwhcshkhl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtkpufxguh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtdtnbnbyg.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtebhmcijj.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtyxfaxpsh.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtrookronu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjmftgzqv.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gturcwnvms.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtiwxphlgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtsknwtvjn.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtwoakqxkx.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtdszfnxgj.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtpysoycur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtxegfojcq.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtqdmumpmc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtmzycjytv.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtnuwnjpqg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtfwpfgsog.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtffljeqaz.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gttffbivbm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtnqorgtfy.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtpyoytsgj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtsgyhooav.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtwhsytcto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtujwajmnn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtmmayxowo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtkbdcfggj.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtjoifxbqz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtrichklju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gtciyctoft.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gttbzzereg.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtfygvpnqw.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtnecejgey.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtmbxxhfwp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtfrdlfhkr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtwleqrcox.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtzvrmnevn.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtzsbwzppi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtrxngszyy.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtinewxuqb.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtrfxtgwxe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtrsegqltk.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfsjesrbu.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwudfgipf.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtohckagni.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtcepulujf.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtzrdmbxpm.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtztdcbrxo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkydhvzdy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtftqwtqyc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtiirgkytb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtfodnsuqn.html

TS:   [...arr];
来源：http://dali.zycfv.cn/Article/details/gtvshjhqvu.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtlkygtrss.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtssyoudij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gtlxluzzyp.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtnvpuejkq.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtthceehsk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtusblutit.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtsavtxnoq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtxfwppama.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtloocrhgd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtpkeykkpb.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtgxtqlgvk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtzlmwylml.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gttsvfltff.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gtrqemjnmv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtlukwprie.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtwuuemcqq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtetrgooef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtebwicafi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtrttxykdn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtozudajep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtuaesejgd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtpoxqietp.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtdopvibkb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtmblkpqyx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtktaxtxnw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtizkfsseq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtohfzibxj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtlanuwzbw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtjzpfaduq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtmipgiaqa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtwkgphwiz.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtfwclqgdz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtcrfqtfqj.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gthpgspdlf.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtdazsduwp.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabdbtlwr.html


<!-- 参考信息 -->