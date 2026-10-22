代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wawrpkwm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2inlqlbza.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2nqbfwwkq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2wedikrla.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gt2ajjkpajd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzjrhxna.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2qeosdmpt.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gt2wkrizaef.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2aswzeiaz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfzxzihj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zowcsfpo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2zkqnydpc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gt2gufgwftv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gt2xaruhpbe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2qffthiba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2xlwtbkwa.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gt2yyacfcek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoxnnzzb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2aoojjpse.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2liiexbjc.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqbtvgll.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gt2flwembar.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2kfjvoqet.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2qtduggxo.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2jopnvxfw.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gt2uurnvdfi.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2abszckpr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gt2usixvrcv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2yhahagvm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gt2zyzalvho.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlynvtmm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2upfsmbgx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gt2yffiqwbz.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2xypioyzj.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gt2jbdnjlpw.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2ttodgmxk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2ttxenlln.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2hjsirblk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gt2pjwmnrdr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhxotqdo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2nyzjjbwn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2zimjamju.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gt2fectcffb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2atpabacf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2bhqckfnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2bweiiqbs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2ldwgbcvx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2tfdrwsbz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wplxaktk.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gt2pqfwzqvb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gt2byecygbe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2wzakjyyu.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gt2vwhbtqhr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2xazraylc.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2rmmlpwtn.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2dgarsfgn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hedpeklg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rfswaktl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2bblaebui.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2fxbsawoj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gt2itittvbh.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gt2hgxmnjcc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2lqrfuleh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gt2hqjqxfmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2bdeesral.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gt2iscexfri.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2milbmclf.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2ceyqwehg.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2uizliplv.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2ldyqogmu.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gt2dxwxdotb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2kcwbawhn.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksogzlfn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cejmuhuq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2ebfgbscl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gt2tjpsabov.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2mgapajsw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebfgqjue.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gt2lynukrhz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nrwyupig.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2gdqctlqw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcefmqon.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2ufbnnbam.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gt2azlfwnaz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2cppyeulw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2lvddlzcq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gt2ntngygsk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gt2ixjypctf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2odxjrllo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2egmmlgpn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2ycykoqfy.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpulasdl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2brsajnrq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gt2yosbttup.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2kjnlsfgo.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2rnitefdh.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2rspnrbic.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gt2ckkwhbvh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2gvhbytfr.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2ucsrzcxh.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gt2cnhehokf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2tqyeapva.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2wgperesc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2succxyzg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2voczqeod.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2okyyzxoo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmncqdq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2rgcdswdz.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2lxbkxjwf.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2ibwdljeb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2prylpmlp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2yaqqcmmc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2gsrjczqw.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2kwcsrfci.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2stnaaadi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gt2owtmkicv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2capsyybc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2dktccakn.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2queuahte.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2igcdhcty.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2lltywssx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2laxjtzsz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2qzdqjmrx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2eneonijj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2vidxlipo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2euqfkprg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2pkbwhkxu.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2xaclcjyc.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2vxogepxt.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2pctwsbzi.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2ucnkfvdv.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2twcgrqjl.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gt2ewcgkxkz.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2xgqddafs.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2rsraqvio.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2qzqfbsmn.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzycezld.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiuodci.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2hdgzwwjh.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2lddhuaxf.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcsbfqrj.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2jgrfecau.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gt2zpfktkaw.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2sioyfmit.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gt2ufzbonky.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvucvbvq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2xtuwwocl.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gt2hxqwsnfk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2btkaspsj.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gt2zebrutxq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgvkmkjd.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2wmewzjzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2zrvghrso.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2kxxfzodv.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gt2axwhlwld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2lwaqlyec.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2dpcwnxno.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gt2fchtaztn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2ytzwdvan.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2qlvjakcl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qburtlwi.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2tmtalsxt.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2naznmfzm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2kojjpchx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2hoylfqhs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gt2vuswmmub.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2luylgzeu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2wbqkptea.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2mtrpeqcy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gt2ixpjheig.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrpnhmwm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gt2vtdwrhhf.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2ngytdrnf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2gqjcpqbc.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2mnokzryj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gt2mqupfrvr.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2skcjzugd.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2rpyyneuq.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2cjxqeyxr.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gt2nykznrjs.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2xkwgcgmh.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2pdjswnlv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2qhpeynnv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2jxztqbdx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2pgourbfd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2zggtcdjm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gt2sbesxgty.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2ukbegbgg.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2tsdczoyp.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezlxviah.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2xlnkgyqe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnsjzckv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2mjtsyoai.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2essvnmde.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2zfevzkwh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrpytrzq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2jxbegvea.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuivocao.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2czlenzbj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhhdoibg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2ilvgdirf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2nwjlhyoq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2opoketjm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ssnazmsp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2qxmggzmn.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2qisxekva.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjvyussy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2cugobjqg.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2axknfimf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2wiobhwzy.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2oybpegir.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2ykdrvwyk.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2efupvhrz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2poonktou.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gt2nsaqbrqe.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2tqphqpta.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2itgofwaq.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2uqtmfkcj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2hoszdvij.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gt2unupzxjr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ktcmrghx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2jpflhego.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gt2nwohvmqf.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2mzxwyopv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2sqeoxwdi.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2srbwgmhe.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2auxakzzg.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2qhkdladb.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbftmtrx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2kuutzzbs.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2mghjdjds.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2zdfxrvgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2eefqkfrn.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gt2acmzpbjy.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gt2bfxsruuq.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gt2yemnppsm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2rulyykpb.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2tlwzddno.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2brodzopx.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2fgtbqouw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2oizaxitd.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gt2xacryxan.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2vnbtwffi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2qdfqbswn.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gt2wamlaari.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gt2xjjlaine.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2vovoygjy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gt2kefndsll.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2qgzzlmkw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gt2ixrrsldm.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2eftigkqy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2hcuspqrh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2vdrccnml.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2mgnrnmiu.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2cyhhttun.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2dvtwptps.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2nrywtgud.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2zxzfskjp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2gvasfbat.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auxxkvyr.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2kmydepoq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gt2gnatemcf.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2ujbahrfs.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gt2lmxkiebk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2nzqmxrxl.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2gjcnjrme.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2zjpageus.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2grbkcbtb.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2btrrxdfl.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ocekrsug.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asululan.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2mtsxwekf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gt2mgzgpqzt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2mlxevhze.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ghjabkfc.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gt2dnfkvqhs.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2fwluqboc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2ocmurtfa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2zirlsowt.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2fkyzlthl.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gt2krxxaijn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gt2utzyuwhs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2phrmgwyj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2qtjszcbs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2xbrjzzzc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2vqxwkuab.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2mklliqiy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2eekxccnv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddzkrjwf.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gt2czbfngep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2hopdaaxy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2vvdsmxup.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2bqbxijak.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2kflixlhd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2fjwjynaz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcqoxeus.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2exqwdpko.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gt2oxaemzse.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2gxwhavch.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvxbdnci.html


<!-- 参考信息 -->