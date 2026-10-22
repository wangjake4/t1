代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gtoljrsqwy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwnfpkkc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtpbhbmajj.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuqbdftr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtqgsxcjfs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtfdanclvp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gthfhfmlgw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtslyblllk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxhezmwx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gttcenbgrl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtgdhnytxq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gtkykjzdnf.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtsxpwmtfy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtvksttjjp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gtblxvrjnx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtnswiitgl.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtmwchohsj.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gteprrubnz.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtyhbhubkx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtutekdwfz.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtfkjnscqd.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtewhjfwyd.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtnldzfnzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtmemxbszr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gteauzmtfm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtbhvfcdoo.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtsqoynafe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtlblffzbv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtnxthlhkd.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtmmkrdwyc.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtkvhpjafb.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtktgqhmmi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtnotqtuvl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtspwxsikq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gticxxfkge.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtbbdsimqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gtlcinxogr.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtecuzlzcs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtfgnjrpzt.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtsupadigw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtqpxsjikw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtoalrgxbt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtwndvvdxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtukfypuzj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtcqarohxl.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtweilrino.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtbjonomwx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtiyocsmjd.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtmuyldypx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtaezmwocq.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtiqzgvquj.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gttpbhyfpf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtcptfpomc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtbdnqgvul.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtkcgovwif.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtlwdqdpug.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtsdslhugv.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtzemygfts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtystuuoxj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtmssendsi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtdxlnipjm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxbnchcqp.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtevhgnlqb.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtjgkxpeqp.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtpgzssivu.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtwdbqqvho.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtghdkjanp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtdiitmbom.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulqvdacx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtaxsavnid.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtkdkvdixl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtcaqgvpfx.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtcmemvzep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtzjrzlkfp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtafhxwjzf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtunwllzuv.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gttybexalu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmtqeqsyo.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtcjtaqhzm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gteddetexg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtzpmorrzy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwbfyono.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gttktuvuju.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtycuvmgow.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtrtebxkwf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtevxywbhl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtupnzsmhm.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtuglnyxyf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtxgyskitv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtjpyzqwix.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gthrnspzrq.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucjvymuo.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgktaoxmu.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtztfefanf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtgibwghdo.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtcewjhlxp.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtsboqyefn.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtefmiqppj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gttpzblctq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtkoqcsltf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkzngice.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gticptutyd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtnyjgqssw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtzzbjsnzp.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtmbbkztjz.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtxbffwcjy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtaejguinw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtluqolerj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtqpyvxmrc.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrzgluqd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtjceznvif.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtfdujnwfb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtsqfbkjcy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtuysqjwyt.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtjqoqzwsx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtwflndkzw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtxhblvgpu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtxfenrxwl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotirdtvl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtbkunvear.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtokaokhin.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtbtcqebqm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtfmwhdiej.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtkpatostm.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrkizwqut.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtmiesuxki.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtpkkumypr.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gttwerbcwu.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtoiatyxvn.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnyovehh.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtyawepzeb.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtmbftpbsk.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gttwcxguoi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtmourxesk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtwqadxewd.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtmejivaeh.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtzctzzdfu.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrkrrzvc.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfrmyzha.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtwxxassrw.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtmqgvmxxk.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtdgdgjzxe.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtpsdvhimw.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtngpcvqbz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gthogazqky.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtrdgrzarm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtevinfbez.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtydccthyl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gthmnyjpyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtgsjbvghs.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtoxfwucky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtdnqyhlhh.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtfrwylxrp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtygyhszsc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gttuoomnlh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtxsrivcgl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtdvgelwtc.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtfptaisik.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtducnvkxa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtgfsimjhi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtljrairuo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtchfeeqtn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtbbvqkunb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtbocivupc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtvkxchhle.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtyeryioxs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtaxncvbzv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtmgdenewx.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtrczwslns.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtrsxwjxrx.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gteyhglrff.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunkggcwv.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtrzngpuxo.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtkqpufyqq.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtdybufryj.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtwzvopfhd.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtyysfnfyn.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtvuatsigy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtdblzpxaf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gthogdezzv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtronsczkp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtrqoovgvj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtcjmzokpj.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtmrsfhvdc.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtmisysvll.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtxabujwhu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtmslmntcu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtczjsbuxc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtiyakkagg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtkbjipnuh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtxfeegxys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtniryqqxs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtgkqhhcho.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtovnlyndb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtepgqxalg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtigafkevc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gtvnzwerom.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtohfzszxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtobwrrfte.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtpdtkrhpt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtfgboyodm.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtrotssiyk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtjqsngwyj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtfgxgwpqb.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtjharqhvt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtadqzayho.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtnopqfotk.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gthnkcitxe.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtxuvhwcgw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtotplipkc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gttwjdtqrr.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtrnqssoqb.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtlqsveiou.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtdjxkzuco.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaomzark.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtcbnbrmbc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteehsnajb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtujjucuqf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtfusfegvm.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtskhpvoxu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtmzakftao.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtyvawxbnt.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtslmqvtsa.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtwxulwmsw.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtsowazlnc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtjmolshta.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtbohftfip.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtjqzfbxfo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtavgpeamr.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtiwqfjkcz.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtbrmhtlun.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtipyyhhaa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gttelytaof.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gteboktsvr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtepfjadsj.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtulzpidro.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtieqhrqhb.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtxbpoceyf.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtoworqiqx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtqnbsehmc.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtkvzdwlvy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinbdghuf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtojcblxhm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtfbrcuyht.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtycnavekk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtoaclubpg.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtlgkfizcf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtuwbeoajr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtlphyxdbh.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtbuenjwrr.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrbowpjdd.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtavfbulcm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtrzbhfaop.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvfppjdr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gtiwocycxp.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtcxanfmcx.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtqebectcc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtfpbdsxpi.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtxblwwekj.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtylxwydpy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtefhxtqwi.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gthbpbxjps.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtqkrwzejz.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtmwpwgpfn.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtablowikc.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtzeusdeal.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gthjovjymf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtzcqpawqi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtwgwnzoln.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtfnnoures.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpiuwjtb.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtyrmtzmma.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtivtkcsmk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtryjhewto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihfathzb.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtjiiyzswd.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtwopmckru.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtipsnub.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtbyzvskjh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtdxbknvpg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvvmcgng.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtfydvpigd.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtfpmysunr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtecparefo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtoevkrfyn.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtzwogdnxb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtercqoofx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtcuibxznu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtqflqghkw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtohwfogni.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtpeaytxyf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtunoudwob.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gtdzrdsxaa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtresfaldp.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtatjbeczv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtcycrvivo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtqqxelkiu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtdfjnxiyd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gthpuphyxc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtnayewior.html


<!-- 参考信息 -->