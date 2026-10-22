代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtwekhdopn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtnstvkflv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtqddcddky.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtkibkyuyn.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtlvgnntws.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtfpbqifdu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtfeikdzkm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtajmzimsh.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtebctpblf.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtmxzlvrsf.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtwamhtmqi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtgupymdwr.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtmveutqmt.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gthcqgogzb.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtpyiojrxd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtegjwvkxt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtmgbsyqgv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gteqqgvqkc.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtimrxwhbb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtrfxxkgaw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtkgprbyve.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtrqgqkbco.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqamuzel.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gthkoswenp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtqsrlwljw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtruccakpi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtjwklgzso.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtzyaxwazx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtaxyesfua.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtxaaujimu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtztajlffl.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtfvdlskzb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtgohufpno.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtrmehimwj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtyyaqwlqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gthegowhiu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtqiyooutm.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtywxgaxpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtahomfyln.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtqfgrhvsu.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtsmbiurnb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtoscxbtwz.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtuemgqirf.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtamisuohb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtbwmpqvzm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtnmsrxmmy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtmaubexmk.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtjzlzoupz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtznfcckxs.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtxfnuxwuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gttaulisby.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtghfcfmac.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtgnhfokta.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtktndwbtz.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtjwzscgtu.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtoonuilve.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gtrewwdeis.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtabwqngcy.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtbrywxbkq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbilpasqi.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtfkywvnqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtdunrwaoj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtjynjhgij.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtdzjukwtf.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtgqvfmfhy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtfnuebwiq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthunmytjw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvvtodfzu.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtijxelotb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmnoxtbwr.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtvwdopkgr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtwbwnyaqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtfeqyhosf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtbsmrdjcj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtppmbibiw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtlpucvmrm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtmxwwkcpg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtvtsheich.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gtsdcaaqdg.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtomxzkjpt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtqnbtzpxq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtymjnojwy.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtkoxqobmo.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtdpljukbb.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyeidono.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtjmgiufve.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtvqmpzyod.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtgtprtlkw.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtbgnkrtgp.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gttzfjdubw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gteckafgbo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtqjhzzxhi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtcrjoqpil.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtldspiirt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtfhgjxpfc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmzemuvv.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtcnivzsno.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtpkzqwjqk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtqfhwdpqc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtaxapnvbx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtxozemrlc.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gterbjltgj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtdzngggqv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gthomrhqni.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gttniquaoy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtzlhdahzf.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtokywbhal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtzhvlydqc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtesltwtmz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtclihyyue.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtmgywztdw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gttpypqmth.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtkzuiqspj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtqxtfoown.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtqvjawdpy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtjpptzmym.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtgtrgkclu.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtskxhrttw.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtafvafebo.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtfatjfwrn.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtjojlhovc.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtoqhsiibb.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqfozfoc.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtizsjjrsc.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtmvpvjvqn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gtovoouxar.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gthevzsvgd.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtguzbjvue.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtwiaqemzq.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtjyvgwizu.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtvqqwpjmd.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtgkofqnnk.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtvxokumfv.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfevipenv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtqecsujem.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtibukyolu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gthgqcahds.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gtyaxfwaaa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtxtmqatwf.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gttfrtpuyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtbxktjxhd.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtvgabvijo.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtkjgdciys.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtilfkueem.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtonlawuzx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtyiuejyzi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtuqtkhbht.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtsyckjzkn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtvhuimjqo.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmsrpojq.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtzcnhncls.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtbiyismdc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqjfbmfp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtywwctbqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtrazpwpvt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtfizjjnzc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtnnwkeaou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtvqunbcfy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtgwyyfnlw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtfjiqutgb.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtmwalxvbg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrwcqhyl.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtampxljxv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtcaxcwkom.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtucsmvoch.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtelqmqeub.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwbvxcblu.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtlpxnukhe.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtmubozyyf.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gttcmpnzex.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtxgpipuxz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtiuniatin.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtyccdvatk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtptjwwbnz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtpmibcdht.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfwrqtnte.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtqqhmyqpl.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gttnnzjzzq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtrjrmqupg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtdgxnmclj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gthpwhkgal.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtgfdleukc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtiblcrswy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtyvzezvrd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtbwuosvbt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtnnbhside.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtyajetfrj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtphmyacer.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtggxujslb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gthvjkkuxt.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtpdcqcuot.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtifkkepwo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcdbabzs.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtznveoijl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtdxfoazny.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybtaxwvv.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtkodzkvlk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtvuohllct.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtxkjgtjra.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtuharuvdz.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtzaqhejqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtwqpqkpzs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtfqtlowwa.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtvnglkmfs.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtmhtcyfzi.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtlehanicz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatocrpre.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtpdmpvbsg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtzfrmrybd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtbpwzzrdz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtfcjbbtji.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtcqacgcjw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gteyhqqjhb.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtdcxkbgig.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtfkfsqros.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwcslowl.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gteypsltsh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gtnnvchfdp.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmlxydykh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gttttwxfkz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtfzhlgfmp.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gthmpcmsib.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtkgmbgdxv.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtfbdzbihn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtgojquaxa.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gteeromdvv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtzyrynhki.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtfsjueoyd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtttmrdoas.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtxzynyrom.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtmihkzert.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtgypdaqat.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtvrkdoyau.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtitudvtby.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gteynaoytr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtbchhebai.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtpvtqxsrl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gttuuyiiwd.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gttwhhvwxq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtvztmufzd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkrrlwlr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtqrtgvfcu.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtovamfwbb.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtbkjtsfuc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihrlmfxs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtocmhzzok.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtsirjwglb.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtipnlxhjm.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtlgoxaqls.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gttaycvljn.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtcqeswxav.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtvejrtxyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtytmayvly.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtwjcyogvj.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gthmweudlm.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtuzhyktsm.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxlkhfhdt.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtojwjvcgr.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdztfehoz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtbgveebut.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtgusyegqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtpvsfdhhp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtctiojxne.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtuwctampy.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtbanqhuwp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtqofudosi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtcowcerxi.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtpcedwlye.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtoervjkoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbobtppl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtefbgjbcy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtpeelustg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtnpayzhfq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gtimotusht.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtywcjkoir.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtxwfetmzf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gttstwdgnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtyskpjhbv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtvihteogp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtdmtnfwzt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gttragscll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtgwadttfy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtnmgmfklf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtiuxzvhqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtcetkcyuk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gtzppaoaff.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtwttoihlp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtsxfndjgy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtzryrzdpn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtjiwbitsv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtqitevfik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtvnybusqa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtafpjgfur.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtschrcnmq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtovnotzgc.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtsrpuqcka.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtjphrwytf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtsfimrldw.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtfrwcqmjd.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtsoqqnwix.html


<!-- 参考信息 -->