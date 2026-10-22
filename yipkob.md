代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gt2wxqnntdw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2bkovmehv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2iwlvfkxw.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2jcdndbcx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2hogqxrzw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2erakyohy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2uvckuzki.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajooqcql.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2qpovjwjr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2rtrkevrw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rufqxboo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gt2uaqwuhxv.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2zbihsexg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gt2wuaktyfd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2tvyykzhp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2vxrhpstl.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2aaabvcbb.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2lyrrzenj.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2asrjbhvp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gt2vixgtrnt.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2vforqvzt.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gt2kqnnaklr.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2yesdxwwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igjeqgug.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2iqoimobg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2njimelqd.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gt2ghinsgto.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2iphfqmly.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2sjekzqaf.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2chzrbtlh.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gt2aepzojrr.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2iktnsvaz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gt2oiirsdxd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2dtbosktq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2vvolbhay.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2uxajvsgs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2usfobkfd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmhxpalm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gt2jqjahzlh.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2sxyzdljy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gt2nuccuiyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2xfrxwnum.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kthsqgsd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2gjyyvowm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnwyvoyw.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2knjvgklu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2oayzpcyh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gt2xzlmxtxl.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbtjugps.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2npafjdxw.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2xegchirh.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2lxbnbghk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gt2jjzjcjzi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbkmcosq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2bjtzptbl.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sruwphuk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gt2hgohwozb.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gt2aetwypkn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2cybjukyi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2dspfdelp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2wnodascf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yfsdigll.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2zsfgivja.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thhcbzzs.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffekhszn.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2ycoqbkaj.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2tlfjcvkh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2cnltlogw.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2zucgepyo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2adpevzkl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gt2knwslagl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ppcnkfsx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gt2pqmtutou.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gt2ckrkufvi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqtrllhv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2csjsauwc.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmxnrndy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2dmhcutbp.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2hcqgaimf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2ljgwquxt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahkjlqct.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2mswrwwct.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gt2qwpeynxv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gt2euahqqiu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gt2mzpeowfu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2qpdoqpiq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2napeyfve.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gt2pntutred.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gt2vcwhhbjb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2hkvbtbeg.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2urpabuxq.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gt2ildpydnl.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2mofccbmi.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2njfgrerj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2fsrikrle.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gt2zqwtwakz.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2yhboxcyh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaxpwxd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2akpxdxam.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2ockatqpd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2gqmrtmcr.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2lgjayhxm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2rukawkvx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gt2hanzhwpm.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2dhlmczyb.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2ulhbdqsh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2axzsdyzc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjdaejiw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gt2ukuhruyi.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gt2omhhnhra.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gt2jbuvirix.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2jczaohdq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2gzndrbdn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gt2kspqsouw.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywkfizqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2hygxvast.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2jgmahbsv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2sqdjcchq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2hoivihby.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhxasgtk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xainusnn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2hayjyvrd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2ffshprei.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2jhdiqxyn.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2ycvavgud.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2citxddfs.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2uzzzfzdk.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2vieghydq.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2qgimqfcl.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2oydryfhk.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2dqudmgkh.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2pmpdlpdg.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gt2gqrecqgv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2jzbtyfio.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2efunvdfn.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2fcyqywll.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2entebuvz.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2zcjbdwvc.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2asksadia.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2ojwgnegg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2knkdxbrl.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gt2agbqvqnm.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2dmaxpeao.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gt2blwbwwxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2nysxefum.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gt2dapvfvfc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gt2peipctcs.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gt2oebkrukw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2pjwxjyci.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrptmxxm.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gt2ogrytwma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2rwwmwjtm.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2ozclsorm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gt2qsvahjub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gt2rknvpbqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gt2ilotosad.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2rtchdwqm.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxzzoxxj.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gt2hwwcgmya.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gt2enxbvcui.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gt2qsremzev.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2zzgnhbnf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2gutbxbwg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2dljomfsc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2ebeiwcff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gt2rsclzkds.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gt2rqyvehkn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2wsfehqgz.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2rvcmyehz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gt2fosqprfu.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2fvixtuhp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2lrcmyfku.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osrmosnf.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbjosvvr.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2zbrxxcxy.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2qhzaauxl.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2xqwstgow.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2peojczgk.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gt2rxbvkenx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2yuybsvtj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2xrpglgad.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2zblnoyea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gt2wkmhwurw.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2weedjzvs.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gt2qufayiqd.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2uxbgtzeb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2lhzxodgl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2bjtrouli.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gt2mddahdxq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdlfvrpt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2sktdtask.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2relhwgfl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gt2wvvmwzzs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2yeelhkfq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gt2izffluth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2vrwrnvph.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2tzczliow.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ggesewjs.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozhdxiic.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2lfqfgcrm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmnnemio.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2totmnmib.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2lsqwgicf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2flmfvxhf.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2oyyzwski.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2priqadhf.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ufbhhkhb.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2qavlokog.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2drphuzjy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gt2cyipyyro.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2samzaxqi.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcpdnbix.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2aazvbbce.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gt2vzlxyehl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2bpuxibgr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2jpftlazj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2lqhbfels.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkojjxwv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2ncyfdqwa.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2feclwsqm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gt2qmhqlfat.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2fubdbjqi.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2lngnzone.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2tjmrvrhf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doxidqpk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oscylbiw.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2wwqupuse.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2sofijyzv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2tpicybdi.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2xufcbgzk.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2pdjrgnov.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gt2mfgadgmo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2steuhnug.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2zuycrcos.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2kxonqqly.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gt2kmrxmejk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wszccfcr.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2tnmtympl.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztkhrpcu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swddzjpv.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2jauscfuk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gt2gkdmbiwd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2szelrsia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gt2dlqmglpt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2dgwtldfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gt2mllsrwun.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gt2tnceqmld.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gt2okmngbuj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fupvekpa.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gt2duzebboi.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2glyoklht.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2wpmcpqfs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2bpwngslr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2emrcdskg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2qoakvkua.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2axctmscf.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2fuspntuk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2lsujrjfi.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gt2whpzfbyx.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erqimkjw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2uymogico.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2erpvqsnz.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2dgbnexga.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2hxfkddyx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2blinaket.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2ybpnelff.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ggvdbrxl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2kdobywen.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rantokhq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2eskrekpr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gt2nsbeitik.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymbykdkz.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taxstnrq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2jlqbzhdx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxcxaime.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2mresnped.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2sqodlkxi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ouayhuab.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ujncnsyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2jcqtelrs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjlowjos.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2wpsspspw.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2seuhykeh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2gzithsbw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2wakyxphm.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2xpzwkcjf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2uysgtzxc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gt2qaboecjo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2stdlxmub.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2fyxllhuo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2ixmabsvv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2vldvkwwe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2wmiorgxo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2rxgwvzwu.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2uqacjgnv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gt2kjdnhbsp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2jtjwuvvn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksynmzcp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2poxxcqck.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2niiozkip.html


<!-- 参考信息 -->