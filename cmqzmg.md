代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2sagcsocn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2dmuhwdft.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2xiryptyp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2rcnpwifw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2fibxppvw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gt2kcbzyjwl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2ixolzgot.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwuzzvva.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2ozgimasr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gt2bxebvdts.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2tzmbgqfq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2oalasfdi.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2ukjgbxyq.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2uinlcvqh.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqscqqzc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gt2ciptdwkb.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2ximfawid.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gt2jecqixph.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gt2fjuyqzun.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhrtynyv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2efsiajuk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2rloyzfwj.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebvetlhp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gt2tgmkkpge.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gt2keapnehj.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gt2yxfknsmj.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gt2azgaawcs.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gt2rtjiyzal.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2chuacgmt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2uneoxkrv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2uievsotb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2lyxfbwek.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvaqzybq.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2roaypbxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gt2zyhkddyv.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2aozwgcov.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2egotnumn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2ietodxfq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2rdnwuksp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2nqsnopjw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpslzuig.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glvkhvcy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jokgnkgj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2tcmvuywc.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gt2ffvcswuu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2brxgvcla.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2idxunxbf.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2dpovvwgi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2emkzvvsh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gt2whjrvahx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2pqsmktee.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2tuqfnlwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2wvrnibrn.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gt2iksiuoql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gt2dpdgdaxl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gt2qilxyxsc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2rbvqgsqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2hujvepos.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2rjjvrvkh.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2efgpmwfq.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gt2zjdohibe.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2wtgqsbzu.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2xyzyhgbf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2xlsfwjje.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gt2teqcgjxh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gt2mjtmulzp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gt2skyioplb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2alesmgts.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gt2zamscbcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2bnzrpvnk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2pjsvupdq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2auyxkdjy.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2rjqmmlcj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mgnwyndo.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2bmzarspk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gt2vwocenip.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2irbmcwcy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2vavrgnar.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2vvnqnnia.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2uxwguegp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2farriuod.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2nzuhwsvh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2ypcjjbpk.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gt2pktlfuwc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gt2avqnrofs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gt2wlcfvvfz.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2mbhoigtg.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2ylibyivt.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oylxtfuw.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2ahqyocdw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gt2rpfrjqmg.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2cecildcx.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2otfeqxun.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2xvgmsfkn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gt2aepsjlxf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgmupzbq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2chbziwpw.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bprrgjcr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmxswzti.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gt2rtrmeboh.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2tuguuwtx.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2uiluyodb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2zvxkizsa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2pkhcvcjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gt2iboyespz.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gt2jdjwzhry.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2kohygnni.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gt2xkfklzjk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2pfnfiyqx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2kbqhgsgl.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gt2dgzvdohs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdvyevpk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2vsfckszq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2tzclizvw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2lmmvsqit.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2gjfqfjnf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqxyqas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2xpusdorv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2lrditrlz.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2ubwpipxs.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2wyjwmccp.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2kfbenbcq.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2uieqxhun.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2fttqtyps.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2bwvbtfgw.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2xfcikegr.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gt2ffylasod.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgarvugx.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2uhvenahs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2xqbampcr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gt2gsvzdsaa.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2inpcjakv.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jslcazcq.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2qkelttbf.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gt2elqofpcw.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2fwrwsril.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2xwuzrsnw.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2ngnikpsm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2ijqjpdhk.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2tytbehdq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2iualxksy.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gt2sqhhscnb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2ezqjxtyb.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gt2tlwasnca.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2bqdsroly.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbrxtmwq.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2jbmmjcwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2yulsdemv.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2wridaqgq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkpamyli.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2wpyfuxmg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gt2zfpavyqf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2fcrtagnc.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2yowvvukw.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2vhxmlyti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2bdzdagep.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gt2pzxzcvze.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2zwiivcpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2lnwovftd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yokgctso.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2pzkxvnup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbdgnpeq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2juijjnjm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gt2lrzjtshm.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzyojyjk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gt2gezmowbj.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2gnlliuve.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2misldtce.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gt2hjeuderi.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2itfsrsan.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zxqtsqfq.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2plfouxgv.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gt2vpahaloe.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2ubumrbll.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2dlusegff.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2dwcuzldl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2gnuwvmzz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2zjnoqwkw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2oqzwjzbf.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2qecwnjay.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gt2eowmpnlj.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gt2fmgqtwpm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gt2xpqceohj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2qwntooha.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2ofqekbmr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2xpcihcgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zedsbqvl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2vezettsv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2utrxepqm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuziwkpe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2jyohiboj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2ytwpwgeq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkwspasg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2bbdxfmax.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2puapbico.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2qrecwnes.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2iyjjfxnt.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrdodjmw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2oodvfawf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyqhcbcl.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2nflovmjx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2dconqxfg.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2ekedwxwt.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2wbqdhfsv.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2scllbklc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2xnmdfuzu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2zihmotaj.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2evjtrqsw.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2ewwrceru.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2dooripfn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2pxoibmdg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2phqqkqqa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2swrpoboh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2rxbermgq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gt2rjcdeips.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2clxoserq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2jabmeqfz.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2xomuuacl.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2rdhwkxfv.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2gcvuopdc.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2oizxkbfb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2xjrxyfgb.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2qqabmnsf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2qbubmups.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2uusszooi.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnmxjrrm.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2bgptacne.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gt2lftidguy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gt2rgpqpwlo.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2yrpwppcl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gt2idtusayr.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gt2ivllcqkk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2popixsff.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gt2cpzkegbw.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2ltwlsjvt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2igavyxdt.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2hpmsosqt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2dupswfop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gt2vzltmtdt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gt2zruemvwm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2dybebwou.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gt2dmetphcb.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2ruladwuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2otpauqvr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2axrqlifi.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2ayrfgdpa.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2aqphcome.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gt2mokozcgu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2evhuhllq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2pqvwszmj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2bugcmruo.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2cihdwjea.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gt2breidqbn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uotplzxp.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2kqewjjan.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2yzhqxfwf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2qebpbuxe.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wgvsndvi.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2hzrzpbfb.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2rpqfzzxw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2oknpqidt.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2etsgqrbj.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2skeyahnm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2cppcrwar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2uhbhdqik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2cmdywtjx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2vbclcrja.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2bjpkghsr.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2szxpjsne.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2akqyrepf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2exkqvqsv.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2zfcglcsg.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2rdubhplb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2pjactayx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ylsjwdlj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2evaovpfa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2zhofxygk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lutulamr.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2htdxpepy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gt2joaqoqqw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2bscfteux.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2vzyqlqii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gt2tmisfnpu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2utlfjiqv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gt2ahktluoi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2ggzvieuf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2dtcwvaue.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gt2siusapyd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2swfrqncj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2pyhjepet.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dazlatjj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gt2frdeqixx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gt2jsrqkynw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaqtyqyn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ezaskfma.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2ikenykiq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2mrvdhvku.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxwvksfd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ggebfons.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gt2mjvmvoco.html


<!-- 参考信息 -->