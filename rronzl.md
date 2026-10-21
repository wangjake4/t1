代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtmdvgehbw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtodyaowly.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtsakstwhz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.c1oappe.top/Article/details/gthkvqhjpv.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtkltxacat.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtdbxpqrhb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtsqjprlpx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtdrgikcpk.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtveekthow.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtsqupohmf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtgcawjabj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtxvyqykln.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtfkierpbv.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtlbxbrilf.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtzjxnbcwm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtjllaaunq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtqgaswtvk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtdgagreti.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtsjzqdsct.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtbysrtrzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtvqzxatmz.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gttktqjbfr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtnsctjpjo.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnfcvupi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtddhareli.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtdsupokdp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtasejknjv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtvcihaqbq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtjcfuzeet.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtndevmuxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwycbwlqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gtukoyevcc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtyzaoolsu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkzwzhrxr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtkfoxloap.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtcdqrcisk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtuznnzfek.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtalkiyhlo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtokxkowew.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtuvpjgpkt.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtwyweqjfi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtzlhitrao.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtmniyvvau.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtcktgmapb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtfuzxytuh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtsrvixbyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtgvksulno.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtujbvomro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueaeipvw.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtgtrubbay.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtjybkuypt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtgunsxqco.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gttkjcfvqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtlpuoyoam.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gthnwwwkcx.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtalgusuzt.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtcwugbwhx.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtgxnuiqon.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtuuvdfoys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtwgtxtizt.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtajhitutz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtdjpqypbl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtbiwvhxvy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtorrxjrof.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtqqcctvrw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtjadmwicn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxdgbumsj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlavvwuhq.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtuygilxna.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkwdjtpqu.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtigrmqayx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtykwbqcnh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtczzrsewx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtgktymjzc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gtvuxeqerp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtotbhmkgw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtsxeobbyd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtvqjrgamk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtpckajwvj.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtjujxxurz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gthpvmmlkh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtwdjnmpkq.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtoosuumbz.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtqzcucffw.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtjopkhejc.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtqnhowlfd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtnvcrdzua.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gthofogjou.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gttmorbfyf.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtlgidvypv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtrkbnupoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtveoyhsek.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtfciafnas.html

Java: list.add(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtxbcquznw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtlwlhcczc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjubzaogt.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtohegokti.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtsaevhzwt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtzwouikco.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtvcwtnbpz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtklxazgyh.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtnsjxhjnk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtppkouezs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtecsnqmsv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gtewucripm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyckvuoxa.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtzzdrogkb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtsdzqhfbm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gthbxbbtpz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtqkidcwhy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwloytoc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtfrrtiofr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtlalfpcls.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtedyzfrvf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtukwxirmo.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtuqukovhh.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtxbpefmop.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtuyldmawh.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtynlkcsex.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtivhbbbdu.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtgbmywinw.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmmewgbxk.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtdebcnydn.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyihlbzcp.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtlhvwblgd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtvbaqlqlg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtkarqippy.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznjhbznw.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtfuokhyks.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtistsanvi.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtfllxdzwp.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtfkflyren.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtmmvrtsbt.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtgwdkfben.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtnnkumntn.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtsfpbssff.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtndbsjlpt.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gtsncybamy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolowgzlk.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gteyqhjdbw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtjotteypb.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtzndzcfzw.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gttkuibckj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtpgpkloci.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtciqhhlre.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtwpgpzzkr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtxeujoevi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtqkgfaojs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gteddqlckf.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtynmnzlyx.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtxjssdxiu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtjpywnywn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtnfsbwsvq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtnfcxivns.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtjldxpdid.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvstixvms.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtnievhrqv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtwhncrogk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gtogoodmgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtfgdkrfua.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtgltuxaci.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtealqawsv.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtbmtuoclj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtnibwuuyp.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtfvrjpaei.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtpzbbejrq.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtmcurwsbg.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtdlyxzgtw.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtbkhbqfid.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtgajwjsli.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtghnvycfn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtxtlzjzlj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtrjspfyzq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtntdlmydu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gtltbngbhk.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtjifulijp.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtaayfhdol.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtuzaszvzz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtjdnlhcgi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtxrkdeqdg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtddxgzwkb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsecjtdzr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtldnsvruq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtvibullvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtvnaiyugm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtpcevibpe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtkajqrtga.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtmdbgwcsi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtjovowzjd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtvopingnf.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtvodezfze.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtpwkbutto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gthoktraqx.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtkhndovqn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtoapmqcta.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtdafaxhrb.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtuzrpjcit.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtlsarepap.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtlnqogyii.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmpvtnlb.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gthmjykhsv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkklacfb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtoprwsgxs.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtgrwkkwdq.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtoeoxktry.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gthfxhgpou.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtdnpgnuxk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtgvoptvbl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtjvvhcyrl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtfvfwynpw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtmrsacjpc.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtjejxvwck.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtflxwxefq.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtvyjrftuy.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gttotjbgno.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpgqguxds.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtjzmkbveh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtftqcngjm.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtmnasxujo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtballwqvr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtztuqsegh.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtcfhngjyt.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtnwwefbgt.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtkiwvfmgg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtdiiclwug.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtbptntcjz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtmtppuill.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtsrqvsqve.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtobffrzsl.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtiftaobwx.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtxsgvvqxq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtsvnasefk.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtckyaavuv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtslqypath.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtxupnsvzr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtkplzliuk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtjojpcplz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtbhfnvznj.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtgidppztl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtfivqvhjr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtlonqoaqs.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtmfhivtjq.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyvjocofh.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtlaobctwx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtglyilckz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtrmfqnljg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtnerrlptx.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gtqzmghtwz.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtgwiucmzv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtkcahrccd.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtlgpufrvw.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtwhwburpr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtvuqerwls.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtgfkfoguq.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtevsfxbiw.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnnwotudd.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtxrvcyxwn.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxqgknrc.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtzsncyfkn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtqngyzfib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtghfpjlvj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtrblyxsgp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtugvrgehp.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gtuhhfdlaf.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtszvymlgc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrogjfpsb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtxtmtoffq.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtpgdavoaz.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtiduxqzwe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtnwwvhecj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggqqypt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoohtjvo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtcadmndii.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtqgjazgvm.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtfiuyeppi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtwokcynct.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtmbivpevd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gteskbfrnn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtrkakaqym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtpoboxdam.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gtpmdlnqtr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtqasjsyav.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gtcslztgim.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtidruzgrt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gttulcgmlp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtyrwuwqfx.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtcizpeyic.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtfccgklrn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtubbiuiqb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpuwzlxv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtmogdcbeb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtfvbhqygi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjxewxmp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtbcogywct.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtihetlayk.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlcoawgjl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtreknonvg.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtldwqnasf.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoctdlfq.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtzajceimb.html


<!-- 参考信息 -->