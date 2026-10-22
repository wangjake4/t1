代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gt2kdzxydki.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gt2krxiyyve.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2aqzhxegw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gt2iobhwsgd.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2cdcaosdg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gt2rrfruhuw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gt2fmfotuap.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2jxmeugrh.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2tcehxufn.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2kgnxocuo.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atobuctk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gt2aqqtczkj.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2yuzlmdsf.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gt2nwnivteb.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtdpkyxe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2mpafastu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2jinriufk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gt2shwoqfnh.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2hmksndbp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2grcekvcb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gt2ceerdhhe.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2cbelrfso.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2mdqwmfng.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opztsvfq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2lmwhnpsy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2tagermec.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxmcasts.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2idwwqtny.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gt2irexevyy.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gt2hkzpvzah.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2pmqhwbcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2fkwddygu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gt2bajdqiag.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2wcaxjysq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmvdftdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2thwjiepg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2povpylzm.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gt2weglahkr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gt2smqtvobi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdewsltj.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gt2syfwugri.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2ayqrcgmk.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2yorywpzm.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2rqvbsoex.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2slbmoiyr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gt2hhaezxrs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2euwrkgyt.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2trszhuoe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gt2ucpikwdj.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gt2qewvgugt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gt2qzkhznpr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtwgjtpv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wvjmcwvj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gt2dajlnnka.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2tvexhiyx.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2absoncxs.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smgcbzkk.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2xlkkzpda.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gt2rpmaoego.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gt2zdpuwlox.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2aadvkoww.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gt2slppfkch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gt2otqaadyy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gt2tuyixjjl.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2ufawehvr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gt2uxchiwtj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gt2ltheukph.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnxcvxpb.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gt2uysnuhmo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2faxwlbuc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvtshqn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2agetiiwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2choygmmg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2aubinvxl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2znxgoilf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gt2ytkzkksh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2eewecjit.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2dvsveocs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gt2gsuesvkx.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gt2nuryhmur.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2zmmopqyg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2cyaonyrq.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2izsvtvkb.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2gqljspgd.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gt2ipnikfdz.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2mslitatg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2nndcyqpx.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gt2tmpdlaav.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kycbvfsb.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ebjhshra.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gt2kltttkpx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2uiolzelw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2icweaibn.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2wfemugkc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2zqnytamg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gt2hlaiinwe.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2xgrddabo.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gt2jpvsapvo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gt2ikjfrobg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bzyfslam.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2psjamopk.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2fwvkrvyc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gt2elnixahb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aphzugxn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2dqunsmfe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gt2xbwpbljb.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2ivcqlcwg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2tvhgedmv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2kvjijnyq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2oakpmpij.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2qedotlro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gt2dsvqhosx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2iqipnzfe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2deqvwyre.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2krphwxqj.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2fjhrayid.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itfxturu.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2jzldpzcg.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlxlzfso.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2nsiupeac.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2xxifmgqe.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhnahbsy.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tabirqza.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gt2isxukkgi.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gt2jtcxaavb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2bkvarlkj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2mryjeetb.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2nqljscun.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzgfwekz.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2fqcnjaul.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptyeayvm.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2sfcmgqou.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2jwkfwjqx.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2qsrhvhod.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2kjqearuj.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2qvnhfqto.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gt2eebqratq.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gt2eiqkvwaf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yheqkfwh.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gt2xwxachfq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2pwwzhmqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2jmlzgwrs.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gt2uhwkttzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2qwyaouxc.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2vubecgds.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2iygotgnw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2copodevh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2ajpbvxny.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ekowqoyv.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpveruqr.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxyvmwcn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2zkipjqet.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gt2kruvchus.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2tweksgtz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2kcxcwmsr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgsetzp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2pdaljweq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gt2csfywwzk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gt2evgfdect.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2rjilhyck.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2jrzqqfzd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2cxetaame.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gt2nvgxywlj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2ckkmxylp.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2nkjkyfej.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gt2fwuonavl.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2psxznexp.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2tquwysid.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gt2afdragja.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gt2wwyqzmwl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkmwxcrp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2wzahyhwn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ilouxkig.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2rygimufx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gt2rdauyqyc.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdirhmhc.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbcmtghv.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2rogsycms.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2mhliybmv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2xhwfoypc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gt2qgedbvuz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhpmezym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2argmmhuh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2qapukgwk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gt2qrwyewow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2sdhtftfs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2cositahu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2gscozokj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2ahgwjmdk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2pmwenoen.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2vbxdkaog.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2efhmxfji.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2efxlgziq.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2unxsrcvz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2reguojoi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2lsgzxepc.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2ulfzcobp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnwpirfq.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2jwcttqmh.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2xckqcmtn.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2tndkrwik.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gt2fmksipfj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2fefbwcdu.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2kukhufwu.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gt2qsfsldhl.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2xtyvtdxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbaoplkl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2cgwzmqyu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2rfjhqngu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxximfzr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2ajsrakxx.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gt2tbzjnlau.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfpaigre.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2vmmpppgp.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2eocjdofw.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2fnxmywgh.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqitkcdp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gt2uktqaksk.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gt2asdocaup.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2xhpqjzft.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfovlgpn.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gt2hlahlpyn.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gt2hlkonlye.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gt2epdgqvto.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gt2dcxtyyvs.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2ksomhmxr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2wpufsrvb.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvrlrtti.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2piiechyd.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2rqvkfkml.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gt2mkkwnsie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2wowjhdgs.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2ajmnslvn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gt2urqxljld.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2pmebprzc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2mzkqutuy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2kcqrkxey.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gt2eiqpkxat.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gt2pokinzfs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gt2tejepfjs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2eumlpxru.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2jrwfgulj.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2xghmirqp.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2nfbkauci.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2jnjgsbzf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2stzdpute.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2dbeakfkp.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gt2qbmtzurv.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gt2istbpqaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2ggjwjunt.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gt2hqyfposo.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2bcowjwth.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2erfkrqow.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2jebvrjkf.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2atkullro.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2scdueerl.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2pshufmsw.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nhwrztkw.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2iwwoofiw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2queryczj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2libklhcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjzonpxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2wttnerva.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2upolwbrh.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2kuyyfizo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hthzdjle.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2tfcaaegz.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2pxemezzl.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2ychsqyen.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2osnexgfn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gt2kzbzazzy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2fzkazkuf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2wuntuvyo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2ftmfwtox.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2jqsfvhyz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2vzikmall.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gt2ddhwedim.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2ksjssewf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2xwifurub.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2nsonitcs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojlzamtt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2eogtewkv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gt2bghdccuv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gt2wkfdzsre.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxbpnwww.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2ctijupch.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2zflkxlog.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaifihas.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gt2pzarmirp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gt2tgayiyim.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2irxjontm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2ambjevql.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2uunirgaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2qdnsqumk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebuxpyxp.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2foalufae.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2ocmhfyzo.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2rewevtda.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2gythjkxz.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2mxpqqagv.html


<!-- 参考信息 -->