代发 wailian999

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtptrnrvrz.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtiwstevoy.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtascplcvd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gtgfotgtnr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gthqwyisge.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtngvoymdf.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtjdqgouxi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gteqczqzlj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtywcedpkk.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdzeyeim.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtefbxzeuh.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtijthvbjp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtcdaktktr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtfzkfjzwu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtubqadnmj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhrfggat.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtggvxweqz.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gtuvdfivbf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtxzcapvdf.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtodetmeph.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtdmavbnry.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtpejtsmqk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtytnpzegf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtauqwcydn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtqaktiseb.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtlapfpgnx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtkwvnqkvl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtvkdhgivh.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gthidqwccc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gtwmizudlg.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gthporqwng.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtctzxbdyl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtggwikxra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtgpzedjms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gteaxbfvkc.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtqpflejii.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gthkvvzjie.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtrvbiplmi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gtwcajffpw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtmmtnzuhi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtkkazqygl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtaqahgrsc.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnqbeaqh.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtwlodtjle.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtkvbrhsex.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtvfkfrllz.html

[C16] 函数 / 方法重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhzyaxxu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtxqekikat.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtybnsruyf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtycauwzox.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtzjwylysr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtsitxwelp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtxnrdeund.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtvhzbhjtb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtmpuisdwh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgidokmub.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtwndavsvn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkymgkvir.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtmriwiujf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtaoehpbaa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gthgrkifgt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtnjmxqqxi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtmzjaclom.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfvgdjzj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtubjsbono.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtwnmrxdhv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gtccvefvvi.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtbvwrnuuc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxzpfpie.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtupiqdcii.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtbocypwoo.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtjtqvpjov.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gteefswmgd.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtbsmncndz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtezpatbsj.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtvrezjpvq.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtfodmkhmi.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtqqsvmcja.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtfiwbbipe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtglwolbhv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtqucrxlul.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtfpcljnow.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtqgvsnnww.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyrbzupu.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtiviqliah.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtjsyboytu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzwzahld.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtermizlnb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtcotvfpbl.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtejwpnvdt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuuvowewa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtwkjifqhg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvgcwvg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtdazuvaea.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtnbxpnqwy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbdlobok.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwuccqlg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtcsagkejm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtcuusgeaj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahtifryk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtqcxamphu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtsscetolk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtttoxfpor.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtxyazwgqw.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtzthjrpop.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtguaxvuds.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtqvwqriiv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtgbzdavaj.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtiqpzymtl.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtynmrfjhp.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtulvdzzbb.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzhaevun.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtfyboyfkc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtpqfqtihh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtljtbewyb.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtrifezjei.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtktcjvhih.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtcaxvpxpw.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtxjsphpuk.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtjfibxatx.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtyadpfphd.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtrwowuniw.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gtjunchqiu.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtfqimouyc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtdvucpjbv.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtiuxbaeqg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtgmnqnmic.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtmtlcnrch.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtuecbgbvx.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gtkkfivnir.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtnqhhrehp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtgxcccazg.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtgcayavlg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtiylckbua.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtcmbfcatj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtuxapfvpq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtbjndbyev.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtkekpbduf.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtvvxlvwim.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoaptiyy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtqqdxvslh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtwazmevoy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtqmqtlixm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtqcafzixv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthrjlsvp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtxznwopfw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtjywpglpa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtcmsyyyrz.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtelcjhdwf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtkaaktzqs.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmagvadu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gtolibzzfd.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtlbbcsufa.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpgvmkzz.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gttwpmdcvf.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtjhtfbxrc.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtojpyttpg.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtadqwgeka.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gttokgqngd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtrgbszxgb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gttqoctgzx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtgadxangk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gttfsdlrmx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxdvajnm.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxhbhsft.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtyjlcwgfb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtefstxgqb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtinzixuxn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtowqvtqwj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtvnhwducf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtsrsclbun.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtilbqtdnc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtjmwohbxh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtohugizla.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtapnzvxeg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtzgzggteb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtftogamnx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtabolihqj.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtombifufq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtaurnsddi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtymvdeixp.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtdvukusfm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtdhtshngh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtaatbtibn.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtufcudbad.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtgmdlubsc.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtflumzojc.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtkwzdhwlj.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtphtjesyw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtxeloeyyd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtyipxgqhw.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtowrzwist.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtgdgkkxpu.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtjpganoxc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtzudagese.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtqjfngfhf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtnzwyifnl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtxbvxdydq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gtisdxskik.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtjjizeynw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtldwfhsxs.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtigdaykbk.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtlgbhuqnm.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtcaaixala.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtrdordxca.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtdtojrqbo.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutpxutvk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmbguilr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtcskauejc.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtzhckfqgz.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtjqsmngzq.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtjqdubgsk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtzijnbjxe.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gthcotiajx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkrvccob.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gtdbqjxxzh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtfryinlcf.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzcgaptp.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtehuwvxhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtoqurpscj.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtfnhudvbu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtztswfjji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfbxfbiy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtueicdavl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtcolznoni.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gttasazxtu.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtrrudfsvt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtwmqzivsp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtttehaosl.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtcugjyvjc.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gttrhruvwk.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfdowtoen.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtdoymqjkz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtkeygsnzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gtjbcnqmsp.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtzaabidfm.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtuwoasyio.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtinyqjsca.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtfbubvwym.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtwyiolfiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtrxxwxkip.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtuapskchw.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpcrevvz.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsovoral.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtzvskjyrq.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlojbrquz.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtvztsumbo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtdabbxktt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtuazfeejx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtkmjhsdqt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcphvylp.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtnovexexd.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtzvdzoieo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtkgppatil.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtfqeorqip.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtqjkozprp.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtqnardfmc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtcgrpuzvr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtbiguguxy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtnwvnkriz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtynbazpeo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtusztpyii.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtvkychfng.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtdmrgsheo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gtmwcxkikk.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtebacqqxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gteqwmnswg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtnxwndgwi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmjplrygo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtqypgvsff.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtgqldoyww.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtpwpligko.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtxgwetwla.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtiflxmnjg.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtephfjdpb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtztuqzltd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtsohtjjrk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtlckjfnma.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtmnpvesdo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtevozfkoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtckuywofk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtcswrqvln.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtrxfsvtkz.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtqsdngtib.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtqbcvzjhg.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtmrxribko.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatejsjtv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtocwezbug.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtahjvrdic.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtrkntzysk.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtkrkicxka.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtlztqpkws.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpkjggiqu.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtukcefkgv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkqfgsupx.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtpqpvnnur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtdvtnvknn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazaybyvi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtjqnjimdc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtqhtrcpmz.html


<!-- 参考信息 -->