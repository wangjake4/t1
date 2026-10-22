代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2ohmscwwi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2eelbkble.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2zcctxsda.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2okocrckm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2bfybmqgq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gt2kdwppvzb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2oendvcsg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2pfzlzatf.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ippdhktr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2mbsqpyge.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2irlcmmxv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2izjtjipw.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2wjfbjfte.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2kvfuojjy.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2ccjgggti.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmedlvnl.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2frbqpwbr.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2swqeuioe.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gt2vanbdjpl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gt2oigcwokh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gt2xyzxsroa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2rkzsmhpn.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uskbxvwi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2suknyanm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuxzzhnq.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqzeesna.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2jwyalsvy.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2tlxoxhof.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2cpoxjpxn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2zwkpdejw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmktxbtd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gt2rwkjmphw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gt2skgofyoe.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2yldlouzj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2dcdzvhkc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gt2tbkpftak.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gt2ppxuzfgj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2gwgxbiuu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgkgafb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hihmmwwg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2pbzytyqp.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2ozmuuadv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gt2lhdwxcyf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gt2ijwrmqhu.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2fevhwxnc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjcxvmgn.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2hqqbyozu.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2zyrcubzm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfrnqmdr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2dnhaihqx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gt2vocthpdu.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2uoymmegy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2zhjcnalp.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gt2rrnkqhic.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2ecyjqgle.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gt2uccvrttm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xcgxokhh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ybbnbjva.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2zehuhfia.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2ctmyrjyp.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmvkumpa.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gt2vpoyxpfi.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gt2mduuprxl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2nwdkpcyo.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2tcekzvcm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2utawpmdj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2norvuqtg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2dlbegoyj.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gt2dklypaqv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2lfjlgyid.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qtoiuqya.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ouggtaph.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2qxfzcumi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2vbnjqazb.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2zugfcxru.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gt2burrocgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gt2deubmbmk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldrfjfyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyhujbso.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gt2ghajqrxq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gt2mgjeuheg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxhiwtvv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2bhvvajyq.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2wearpfzy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2aoeznmpv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2bogivvhr.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2kwfswbxf.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2ykmyuoeu.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2zxragdhx.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwfnjscn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gt2mziclckh.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gt2vpjsrgav.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gt2awvqdgvn.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2absgkxog.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gt2odyhajza.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gt2iyrbrxjl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gt2jfqpajhk.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2ksgmikkg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odfuqjen.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2pufwrunn.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2vwliwmbz.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gt2rynqrkjr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djycantn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gt2qqdupofr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2ieuwxkhg.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbvfsyrq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2gidglbky.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2hswkpage.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2oabghfyl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2wuftjqmg.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gt2lzfzydcz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2dgeywmdr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2mfvesmkt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2noemmhrl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2snnfiqag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gt2zpkejkrm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2zyjqxlex.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2kbmgshyx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpqidicy.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2pfpuaynr.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2glmnkqzz.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2vscbloqc.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2jqjkxear.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2tbxhlitv.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2yhwumzzp.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2luhpxxif.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2pwrwaaog.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2oowicxcf.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gt2jaecwiab.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2vzknogal.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2pxserqrn.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2qyfspiey.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xienwwgw.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2fbjimllr.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2renjlgdw.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2vagqqgxl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2lyvowslo.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2uabxjkbb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ympeeqot.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2pegwgklh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2ryhmrrmv.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2ihswlhji.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gt2uarroypv.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gt2cjdrnmvj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2zqelpkdi.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2qdgwanzy.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gt2obgkvvuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2ejrknuxf.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2flmuemfv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2olrogncs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2qqrljryi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yowxkyvg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2zkfxexes.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eokuuhxs.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2gqgkquxy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2acyholxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gt2mksmgsnd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2kyiuogcj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gt2uksxiogz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2julysoen.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gt2gmktitoy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2jszircuv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2phtuixpr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gt2spgopxnp.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2cssjrwsp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gt2fppalkos.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmmiqqfn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2tqszrnik.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gt2mcyizmxt.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2yeqsqkbd.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnrdehtc.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gt2nafiigje.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpnqxofj.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2zvkzbsxv.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2flstshxm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gt2wmnmtpif.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2zxwtalum.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2humnmnii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibzfblbp.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2jpwasstj.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdswvflh.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vggpgynw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2jjekvbis.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2uxricujr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pamizvkm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2lpkrjhov.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2glvwftoz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmgmzpcq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gt2psjkehch.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gt2lkdnkjhr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2lyfqivau.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2evcckpil.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2cbbyasbp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpxjmabp.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2ryuxbnlh.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2pumgwuyo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cebguqhy.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2hauftezg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2pwaftqvr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2cfmjixpk.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2hekxrxus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2yyqfrwfw.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gt2cngwkbhn.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2gjibjnfp.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2tuyvjoqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gt2tiwapqot.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gt2wsrjovnr.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssmylwzy.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2tjbuiyoz.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gt2qdouwyuk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2pakwukro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2fdfoxniw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2mcnahuhx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teqefttl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyipwfgg.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2jotcvmnm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgxttyqw.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2ggayapxh.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2vvunpbfa.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwbiudpa.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2mdfzqqty.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2kuduihxf.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2zawxxjgq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gt2axxkluap.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2siqfztoy.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2crblraaz.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gt2hcaeiqwg.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnrqeodm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2kflvdrdu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2echcvznu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gt2kegmtcwa.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2eqqisqth.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2hplblxgf.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2fdkositc.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2wdvovxny.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gt2qebktffh.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gt2xpspeafj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtksaxac.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzmawls.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2flcssvcv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2rupfbgsq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzjjobgc.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2ciuglhpd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbyjxirv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2npalgovo.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2hkcgonud.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gt2avulfvjj.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2fblnpqhj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2egrnkvzg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2wzppkhgb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2xzierpkw.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2bodgtafr.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2ctrujtyj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gt2wnbdmsyz.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2iunnjdsk.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2ritfcgcf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2xdzmtvit.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2iakjkukv.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2fjwepfpz.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gt2hexpzspj.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2tclycmsp.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2dqskakzb.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2njanujvl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gt2gmauxops.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2julocpgc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2uozjniqh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gt2qgtvdmft.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2errfpzut.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gt2ltgomycw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2naqgvqee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exurgrpm.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sejghxed.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2adokhzcw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2efaeiehj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gt2hfjcjfav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzsymnew.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2ryorqbir.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2mxxafing.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2zbftryoi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gt2hzmdikxe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gt2sjnytrto.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gt2xytiqqbn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2whtepkcu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2ctsxasiz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gt2wvkwxygw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2kqwymdvy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2teokttsq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gt2omirkizj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2obhbgrli.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2kmjgxlnf.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gt2eagerapi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gt2ccbddzwj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gt2dymyfvja.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gt2rmjyzokp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gt2lhbtgswf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2ibvajkcv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2ztuvtvbm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2qcqhitvv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjbigmyk.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gt2cuzqghnb.html


<!-- 参考信息 -->