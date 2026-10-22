代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtjpgbstxw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaljdkld.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtdyeegyry.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtnvzawtig.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtypfbjnxn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gteefghcrw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyekwcep.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtoboexxdu.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtjaesynck.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtzatuwegw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtoqvchubj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtsjdgjyze.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtdhhztqwq.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtdhnpeurr.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gthtfenvti.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtvfeilyut.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtgdejoxbi.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtoithbyzh.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtquwslkea.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlropbek.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtirkhyxew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtrzzlkxsr.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtklpfggrc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtrtajpknc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gttupdxdhc.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtildeenyz.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtcrilgnwl.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtaudltoms.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtdelfvcpa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtkzeriqvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtlvevfwev.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtbobqanks.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gthklaiafp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtwrdtdqvr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gthfartfbe.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtjwolzywo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtjyahtazj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtllolryjc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtxbmdzpfj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtnbqzluuj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtpjtznicp.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtvqfavcvg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtmipwubja.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtdszicdnn.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtfyxffmpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtvdhxaipk.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtidtbhrar.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtnjzzzswb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtktotihhc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtuyeicqjb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gttfyafffl.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtdpzspodn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtjeymtdrx.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtxcmukrhv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gthdjysbil.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtuojvhxqc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtybsxnwfd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtenksoewn.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtiglopdvn.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gthdbgnnzn.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtuinfqkkm.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtntjmgmma.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtcmfmrtdc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtbkaoiozz.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtgnwufepg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtvqcbwlls.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtqifdsbuy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlrbfgav.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtkqtosefu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtcxwbnsdm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtuvailald.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtixtwdioz.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtygvycycq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtluvxynkm.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtayzdegxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtslafgnoq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtxzzrjjlo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtlllmkwxy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtpignuucx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtygcofqjx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtenrdzjno.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gthdfyhtxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtxaewpmry.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtsnwwlnlu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtoqxqwmaz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gtcybsjkse.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtaiypjfvd.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtgaoukhuu.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtayrtxoly.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtdfkfcekd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyuvdlvr.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gttpglkjtf.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gteeumcpee.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgoxguwpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtilylaxkn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtttrchndu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtysrjmgds.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtrkjxoxaz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtfiuybhwa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtivorbydc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlenmrsel.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gttxefulil.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtkonfrcou.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtzkqexgin.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprsbeflh.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtylsgnkwx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gtcoeeydgr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtvwzyrjsr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gticlcruhw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtwrzzzdty.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtnrekbxgg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtfdckgfhy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtrioncxkx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtbiiirodn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokpbjgyw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtqsycxgyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtnylktmyp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtpemkatit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gthemcpmkh.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtwqknyvce.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtymlrvfgd.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtaydaqvun.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtkplthngl.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtffdepamz.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtlygekvlq.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfgwgofpo.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtkxeelzbu.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtrmqzutks.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtmpyltcai.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtwvobokwu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtvldpzqqm.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtbmtyilas.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtlsrfxaxy.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtlmysfidv.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gttjdxenej.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtxoifhkzk.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtcxvtpcvr.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtmpuuizei.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtklkbfxzl.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtnalnwzqn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttidzxlfg.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtksavrlqi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gtncnfldns.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gthkwsfoys.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtnieeqevj.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtkcpnjepg.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtbxbbdpsj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtsohlrswf.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtwpsxgloq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtxtwfjrbz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gteaxroxmi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtuoljmdes.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtqybhbnyz.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtoqqkrtnd.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtroacclwm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddirydrz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gteeqijnul.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtlfjlxltn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtloqqofql.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtapzvwmlz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzamknyo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobwgmkvp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtexmcdptm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtvodalqgr.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtpbcprcds.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtekmppicj.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgchrgyul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtuicixqnc.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtcgztuvga.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtkwccoewm.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtoylazdko.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtmwhbxrzx.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtjakwgidp.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtvholrfcm.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gticiijhba.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtodqyvfrf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtovhfcxni.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtwevouvya.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtmnlpbuab.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gthucubxkq.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtlsoohmuu.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtfprlzhjs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtjhrcxrxs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtczqionjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtyczetpwr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtlxzxuldx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtpnuktusb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtycmtqyvg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtzsngsnng.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtvopmbhlk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtvlcfvjqq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwjkkypu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtfbqjzage.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtpmlthwce.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtlvbaurbq.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtktbslkcd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtkfjjxhnm.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtjearyjlr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtifblcccp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtchnrdnay.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtbatrtzyv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtrezhctdc.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtrsaitwoj.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtmdjahvpc.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtmebhwhpy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtjzvlthyc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtxuihdzxa.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtsiwldznm.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtrlmxfrtz.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtzqzkmtmk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtuedgrcgy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtxsjumvaj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtibtzpndv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoicqiks.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtfdabided.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtfdnybwhq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gteialnhac.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtwgzdbfxj.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtysmtmgjy.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkvqutzca.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtsidweeyv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtwgibouuo.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtirifdxnn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gttbwtszom.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtartzflev.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtcvlyfnwj.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtfobrrcfh.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtqevvjcuv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtcghciema.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gttqmugkxr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtywqoajzq.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtbfdiclim.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtvupqkwsj.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtqeycovuh.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtkpysctod.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gtexopeile.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtzunpsrbw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjemmoqhn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtcxwhqcoz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtoxnnljjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtqgvypvte.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtsemvqizg.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtsuvpdtui.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtbafhwyya.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtafewijal.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdknvihqg.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfeltpdns.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtxiddvqro.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtcvaijawh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtgnxbyoib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtpwehqpgf.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gturjihnwr.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtxebybaum.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtnkhlxftr.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtyieaufnv.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtkwvzdvsq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtehyqtrib.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtwtivnejy.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtyfsqardc.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtnbmpibzw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtgucyjzmq.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtainouhsh.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtxchqtmgy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtoidkzsyi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtfdqovpzz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtisrbnsfc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnjsajpjl.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtwnaidxad.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtupkkzjki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtfdrdioqs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtfrzabvsf.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtkiwbbjbo.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtcabwcdnz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdwrhxyvu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtuyeidqdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtkimqjptn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtmjnkheug.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtqceggwow.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtswlephlt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtwxupudoz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtwvjyyzku.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtulljbbmg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtcadklqkq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtfvmgzmql.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtrliqpbgq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtzuojxcvj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtzrjorlmt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtdiyucgri.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtlebtnbdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtbrylmrck.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtscqkvfpj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtzxpbpmxs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gteyjxxnky.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtgvlkojro.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtvwyzuwyt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gthnwilqva.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtymhhvpgd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtmuzvuspl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtezeqgodd.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtjaauvnmc.html


<!-- 参考信息 -->