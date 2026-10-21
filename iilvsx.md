代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtqhvaumqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodbnfrqr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtujqqzdmy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtlwdakygd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtipaaljck.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtlcoubinr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtpdcnxgrl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtiegmjcar.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtvctdznqj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gtojftpdbx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gturfzkbwg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtmuxnlief.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtuflhlkfi.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtfzjommwd.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtualgmlhp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gttnxgahdc.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtwmtnyrap.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gtwesgexnv.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtworbbvcl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtbuzjwppi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtrhqdbwjz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtcynnwato.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtstlzudfm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtikqokgtp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtgjrijwpm.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtntkijgrq.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gtikiakrft.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtwlnqppwu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gtkscqggrj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtvxrjtmkd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtiolwievi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtaeydjtcb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtzdhevfdv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtoesdrtkd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqzphryv.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtpmypzhwa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gtmzcfacdb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtrgnfbdcw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gthkloqzhl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtezhcpbox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtwahbismh.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnncmbde.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtdohwkczx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtyshovmmd.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtzzauqqkk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtpahukrlu.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtyhrwvzni.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtyybwqoxi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtuegmrejh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtbhxeoyol.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gteskkgfby.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtgbhbwppk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtuxgayirq.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtbnjnkibo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtovwjrqee.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gttgynwjgu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtafhwerxa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtplohzfkm.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtjpraqcnu.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gteyyovnae.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtrssndmjj.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtmmfdizbf.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtxgluuhxq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtgbosmdus.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtfdqlhfop.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtxanjhnse.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtlyondknx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtavyngkrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtelnstmxd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtbeeyzxca.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtdqjcytip.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiksitdoe.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtpvvmsjpr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfvcyfzbd.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtgmfucnmn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtklonlnet.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtuymzfhdt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtyvofnqqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwgtmjaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtaplvcimd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtiwpmfzco.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtztzhimpf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtpsqhgtaa.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfecqcxs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tian-w.cn/Article/details/gtfohijyin.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiysuvkme.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtnyjducri.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtmjdrkpjt.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtxzxlhtof.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtkgtzcfbg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtnsvbtvuj.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtgqwgfxmj.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtehcwcifo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzpoyqte.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtjfgqytkv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gttevygmkr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtdyrkwnjh.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtgycwzite.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtnobyppzh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gttrkfxvbz.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtvnprsbeb.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtkvjdxrms.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtaxekzlza.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtkifbxhci.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtggjahvcv.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtvgfwtusi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtkfmwuclj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtcdzublgf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtavkwmdwp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtfarqbtne.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gttnjkenjh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtwvegyqza.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjupiexnd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gthneznxtt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtmvygileh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtqkvqaxtq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtymnfyium.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmxxajuw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtuuncitxn.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtsiydzvau.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtbafrdhjz.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyesfwws.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtzacqtime.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtjjbccioz.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gttpnfshsa.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtydfqtdeg.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtarqkurdn.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtstvfwtiq.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtswlrsibz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gtysdlpdow.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwyruilmz.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtgzzgcvzq.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtdxngrsao.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhcuepbh.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtimoembnd.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtmhnssypj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqasbfv.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtlhdqdbhn.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtjvmskouv.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtxwvrhaie.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtsopvjcsq.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtmthjdlfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtaynzoecr.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtjrlnizex.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtirfyskyx.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtktvqowhd.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtnmlsjniw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gttvrwhjfn.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtcdrjawhi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtbzrmtjgk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwczsakj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtrjgdxlbw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvhsgvaoo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtvdeniyqy.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtloarpjtb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gtfzoommvq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtkfincudt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtwfrswehm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtstmhxibp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtjusjgozb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtslerpgyl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtsjwhvtsf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtizbqvyxj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtgblrpcrx.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtsqldjunu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtuohvmsqb.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtfslwtjdz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtyitlegli.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtpvcwuvco.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtzlziwvuq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtuzchvcaz.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtyirwzxjb.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gttxipbqqf.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtytlwgrum.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksoxdkbs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gthzgkncbk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtzqtgyowi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtwougqken.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gthjnzauxn.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gttolzjfhg.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtmaiforzt.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gtseekmchw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtveytaxsz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtecvcnfji.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtphlebrcr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtgcxridsq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtktmnupmx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtxezdphnv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoovtycy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtzgujibth.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllyequvv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtbsnxmqoh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtdobyoaav.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtqjrvzbuq.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtetzffnqo.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtmlbamzrw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtijhgisug.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtqycijmit.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtfcmmhcus.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtmrlhadbt.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtvhamdlqy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gthbijzhis.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtfbxykxxk.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtqttydsxo.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtxumapywm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gtrxhggicz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtcwscjrqa.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gteiilumrp.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtjesvsygu.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtunvjbirj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtksoieppw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmrlmways.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtzsvnoqzo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvpaxnlg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtztbspdpc.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtlzhkkjtb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtppinncok.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtopcozpjv.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtjpjugruy.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtcsdpirgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtkosayiae.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmzjpgaa.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtyatruxjh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtqkkawbxz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gttbnxaddw.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtulkwykxc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtqnfanhjx.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtyhgetyre.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtbvdkjkzm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtandkzrvz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtvzyxymsc.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtvfqicmgu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtkqlgmorg.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gttwkbdtrb.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtaydddjtm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtlxkskhhg.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtyevnlfzi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtajzodhyj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtgxcabgtk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtcbvexgri.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtvllaswsv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gthvdmllyv.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtfzrwilvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtifnhancn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gtuibrfdth.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtvnmjvpli.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthepgvrht.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtopumicuh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtjzwtjrfs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gttydblkyf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtlqgoonys.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtlavqpbgt.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtscdmfuxy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtouuyecpl.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtuifwumyo.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtlyzytmmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtndkmndcs.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtyilvkgyv.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gttkawfjyt.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtobxmabxf.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtvfptqtfb.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtggoydxbl.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gthqdwshoy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtisfxfozu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtmmgufmkd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gttlxcdwjf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gthjywyqcr.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtqwxbnqic.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtfggoruyb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gthfvnaktv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtuyxoopgd.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtgvapfwir.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtmvplhhfe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtzdojuyjh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtsivlghii.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtlqxnsimk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtlzvwoaqj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtycslmtvq.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtferzviev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtdcufzsqs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtswnnsans.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtiojwbcwf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtsnzyqghg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtartecymi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtnahazaqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtbckjmcpj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtcdapksde.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqztqpqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtqfmzluus.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtplcbebpi.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckkhvads.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtssyceuqg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtevqpgnvr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtzuioarju.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtimfctbvz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtoltautup.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtyhiqnojo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtjtibzkle.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtrrlpgrld.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtvppfwlnc.html


<!-- 参考信息 -->