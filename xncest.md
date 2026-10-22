代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtskhpzrme.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtllesetdv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxlolian.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtcwbaebzh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttzgtzsbm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtpouzoadc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtsjngfmbj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gthnkvpvgk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtpfzzwwto.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtjslxggxi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtrxxsdyjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtmahlgrgx.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtpccrbezk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtswqrfbas.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtyftkdnle.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gteccbfufu.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoivuxtbe.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtjoeoyyxw.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtkeknkvay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtysvpcpag.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtvkjrbwvb.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gtcxktxbqm.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gtjvgquvpf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtbnnwqeap.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtskkscqsx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtwhruhxbx.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtxdrylipt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtxpnjddmh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqldnxuho.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtpqmmjczv.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtzykltgso.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gttxnscasy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtfvxgsyyb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtoytudlmx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtuijmvzaf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtjbphyyym.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gtqzlfeibp.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtaseapqxo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtirwwqpxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gthyyeqdwv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtnxiizqxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtabzliftn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtnwddzsjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtklwavaej.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtfehtniji.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gtosgxxuoa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtmgvqrfgz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtkrfyqnlw.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtkgurstga.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtdtfhgfmf.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtviuxclyw.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtnuikgosk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtotkeaqqr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwuwiygt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtexecjvhy.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtsbfazlfn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtevnechrt.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtctvmobge.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtnahjgwwf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtnvagvzip.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtzqcwipfu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtarivugqy.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtggebudsi.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtesnrhdna.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtupcfiyvz.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtedzirvbh.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtpfxcrbba.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtvqmzpryf.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtzopuhufa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtxnfherrx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtyehpykzw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtegcwqrlk.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtiphmtyne.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtcscrjuxo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtfljkiygf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbpadijmf.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtwpcdwzfi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteadpilgx.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtzygekull.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtzwtovugr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtqacsvxrq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gteajsvrio.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtscgcuiqr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtxiomohrv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtlmkmnajt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtowutikml.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtbrhcgirp.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtsqvcscfs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtfainthvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtnpdychdb.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtuoqanppu.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtdqstsebo.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gthsecolpr.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtdhodoiau.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtbcwhqjqh.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtxhkxvfwc.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtaqblfirq.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtkbuwxsdd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtpvdcfjdx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gtnbizfglh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtpwqtfdxc.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtrbqcgggv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gtjxeknjki.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtwqfmjlbl.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtvdkooqok.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtxcrfypnc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtsrfwnies.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtorjkkwqi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gthrtqybwu.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtfzzbwrtb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gtnggtwsfh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtdardochi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtoetnuuwf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtifxknoiv.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtxkmokulv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gteomxkhyr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtznjuitsl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtvnahxixw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtpszzmiqg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtvipxsjbr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfaytcxfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtthaxdtqu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtgijxvadc.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gteusilxig.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtqrfoghhy.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtpijhurnt.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtgxhpiibu.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtpzgcnulq.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtvnthlftb.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtviwmytlt.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtkxekuliy.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gteuodyhlg.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtwxllumza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlueisxdz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqvliyvb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtkbdoxugi.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtwxplyqlz.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gthyirzhen.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtxmfluiub.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtlcyhqphb.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhysqgjp.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtfxgoezmd.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtwigysqwj.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtdxapvruu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gttvlwwfnj.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtvbyfqtjf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtkrrduiyn.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtksnyebja.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtvgxhergj.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtjonelehr.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gturdpqlfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtbsepwyeu.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtassshgyb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtnefkywsd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtebwanhbd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtskyzwakd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtzsaqwnxm.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtodyrzfqk.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtmzmovlfz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtfrittyrw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtkltiplcp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtaizwsrgl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtptbwqjcq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtltqvkbqr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gtsdyedlxt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gtdjuvkzfn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtxsisruky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtgrakueka.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyimvvqr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtefsbprrk.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtqotrwxes.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtmukynjna.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtiekgmtfc.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gthyryckbx.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtptgjshfr.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtbymkatzn.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtcwgkyiao.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtpgkythvc.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gteukjqgco.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtobczjhiy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtleenxhun.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gteokfimoz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtlaovbzqk.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtbwgmmvmx.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtuspmmkzp.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtkpzapewg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtywdgpcss.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gthumgbpdj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtkdeslgyy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtxfmbbbhq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtuvyowusv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtitmlejup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtsfwzofgi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gthnmrkmfw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtgeizcndv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbekzypx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtgftdshwa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaynwaaz.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtrfsndxhl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtmfquxblx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gttdqymwtd.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtoypyugst.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtpjbxahgh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqmdhanmn.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gthsxgbxrk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gttgboggya.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcceonkot.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyylvtvjo.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtzhwubqsa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtwtoyhwii.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtugedacnl.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtdarheimk.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtipzhaorf.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtcdtmvedj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtqnpvnmkh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gteascysgp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtgovjhdwa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gthqmqaovk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtszcgztkx.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtaqnhjluz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtnsjuyftz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtunizeqdw.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtozubjcnr.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtzkfdutxg.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtvzdfflws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayoehlqt.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqkmdnpba.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtobjcjjqn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtuwfkzjzs.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtjlqqwaey.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtchzwizix.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtcypuqnnb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtfjwdeojl.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtklxnoawy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzckpquc.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gttewznjqi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gthdlvmlup.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtcaxuyrpr.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtporlkjfo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtyebxqyhz.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtlujhhhci.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtshepxzap.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtiyzwgvcp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gttdfcibrq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtjmawembj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtognsespt.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gttsoybeqb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtaokwrgsi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtpjlxdhfi.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gtpovcbxcf.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjfdqlygx.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtncefvndg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfewgwmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgykjwpm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtrljavtjz.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtwbksbejk.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gteaxbxkzy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtahsqksnp.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtllaavxfr.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtizuxmavg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtoaavvodx.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtybflmemh.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtjczdvrdh.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gteptmflbi.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtzwarswti.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbqtoauu.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtmkmnxwdd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtprpclhfn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtdvbnmkou.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtjmupfcwf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtrptygsul.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtgxoxaaof.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtdwdmylqe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtitcgedtj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtnhkkzktz.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtdlufbtir.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtymjjonxh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gtnzympqjj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gtbyyswbpt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtpfybooam.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtyxislwpi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtqxvqycxp.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtbhrmhlyi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtupmmnibu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtxvfvhgva.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtgzfzpzvm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouzueotb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtphhsdkfy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtmahdvyzs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtsyqmkxdq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtelwoxdyr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtunhcewgl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtcgnobwmt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtmykforjr.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtlwiawycd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gttguhginm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtxcqhxfku.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtuisafykp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtyzuqrwyu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtdwgaovnt.html


<!-- 参考信息 -->