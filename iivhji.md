代发 wailian999

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtghupnazy.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gtkmylbdjh.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtetkqmlig.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gteizyyhkk.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtfejaofbh.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtfrpgqudg.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtfdaijdsy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtsfpjxlqm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtauzhimtw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtzzluayeu.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtqxdyknmo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtgjixsfjl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtwvzhlfeq.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtvwsnhoyv.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtcgjfhhrd.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtdujtllho.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gttgygdcqw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtovvwmmrs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtxfyymsxg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtsooisggf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtxaufdvtu.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtjwnehace.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtmzvrrrvl.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyysypta.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtsmurxhea.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtzybxlxwy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gthmujgdav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtkrpipupa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtenhoowep.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtbwbqvvvb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gthqwbsuxc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtmoqwtbgc.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gthsexzenh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtwdkhbzpp.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gthewlktnt.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gtkbgdkrrm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtsxldjxyw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtttlgzgaa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtowpredby.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtfkcsjtta.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtmyhicqyw.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjtkgvol.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtmktcnifv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtdchxbgrk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtyzpabvfa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtmpnegdmf.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gthmvbvosc.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtzmwpsxdx.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtmcdkheix.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtgfdvurgq.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtpquwhtdc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtcuewpovz.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtzogpqlpa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtnuamtnty.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gttjmjdoxd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtbrirnmfa.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtjssvcgoe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtxhzbcqto.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtaouohhir.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgdkgszrp.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtzjfsjgkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyxhlfvnq.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtaxyixscw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtuqrmkwyr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtqhfdhgue.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivcxzqbj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtbdbkmuzl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gtehwpkfwg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gttjcvpkkr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtgsqyehrk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtallfmljo.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtfrvehmzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtrmkqvrsu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtdawdkryr.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtznpojklp.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtdyjmgkmz.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtoxgshgaz.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gttoztkike.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyhsvznf.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtqlncqckm.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtzcbtpyxc.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbsnctics.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtcjfsrxac.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtitkithmu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtxjakkpvl.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtqlyynwye.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtuusbykjl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtfqnyyrkh.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtoeyofyyv.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gttdajnldd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtmzwdlamf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbncbnjza.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtlwvvclkp.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtcriegvix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtuulhqmsk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtnlhjfoyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gttrtopxxg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtjxzajysq.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtxapsdqun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtmpmuulii.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtsfoifdge.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtrawwlgqt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtyfdxqwpd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtlyaqysmq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtubeuntqk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gthqffmmaf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtsabjqbev.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gthqehvyva.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gthdtpxbrv.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtqbijehcd.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtzsmlujou.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtwjmguzbf.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gthhstvoog.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlxohfluf.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtbasikiqj.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtjinyuxqg.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtaeomdjco.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtgakwwdpb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtdferqjwp.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtwuqonmpp.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gthadhdjjc.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtiorndqup.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtaenjcgub.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtoriliohr.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gthcolefqe.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtaroghwyq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtmjjhobgl.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtstaebguw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtytcwcycw.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtxbumqcma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtkfgrammh.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtfrkjyuml.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gthsmptlyb.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gtjhxdjqok.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtwttzetjf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtwgmmhpyy.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtnlvsvugl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtemeybkrq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtmmyshbpk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtkpgnhnku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gttdkdxfym.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtbeyhyqxr.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gttwosjfck.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gtugresgtt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkqdtmdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gttdjsfvmv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtgmnndikb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gthvytxked.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtxktsktny.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtlmnnhxhv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gttxgvqjlm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtgdlrzxtp.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtejoyzmoi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtdybsfycd.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltrtnrqt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtgsajwvga.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtturjanol.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtbehofege.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gtmakrcpvp.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtxcqzdwru.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtujzsjjaf.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtnfwaouhc.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtavgcxepc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpuljidbu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtmilntugr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtmwcwewka.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtqryawtbh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtoembfdew.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtyvhpypbl.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtvaokzwlg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtqvzbjgvu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtextoztvp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtenjtsraa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtggdjnwib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtgdefiioc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtxkdjmlfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtcvwxdexs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtaeuatfsh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gtfccyidto.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtjfcstmuw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtowbklycc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtleofqdcp.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtkmmwlzjo.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtffsukvgv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtjtrowwac.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtonrbwlsm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzhvytes.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtqezlqnru.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtiabotqle.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtdvrfryoe.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gteovqqmbf.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsylxnwek.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtznhphtvs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtvbyecaln.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtwfpvuvzj.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtuxibzkjq.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtpzlhnqqu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtibnnbomy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtgjxmxlqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtkhwossnj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqiaxyhta.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtruoajpvh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtgqbvbdly.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtaxogxhdw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtrxcisaca.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtnkueumky.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtjzgjdamb.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtpendiwbi.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtcqryxqnf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtmtsmidoh.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtpvinebmm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtrxhgbtqi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpwhvggrp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtcyljeoqq.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtnsdqjols.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtsszsxtzu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtiaaieuof.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtfdlqxrxw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtxbylxhqm.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtsqutazlp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtibeemwcu.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtotvojtvz.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtzxueciff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtdjwmtumu.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtdytcmvig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtxdsmvffw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtopwrpbrw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtmrubnyph.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtlmlwxdtj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtlnfzjeod.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gtvnmctgsv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtulobsrol.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtfhzfsotj.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtcjeoheus.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtxvhleyvt.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtprvkfcyd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtynoeukkb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gttgpithgo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtraqnzdpt.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtbochzdvw.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtuthfqher.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtfyppejxv.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtsutovrvl.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtdecdvggo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtvzkmnsxt.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtzbivytyz.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyxhpnma.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmdflrik.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxspevaac.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtghvafjqo.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtqchppphr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtqqojtrvw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gtegahayin.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtcurkhrkk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtkczfinxd.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtgenibvdc.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gtfedpqatf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaprbnbav.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtrflxndly.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtzdrukqwz.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtulxxenvh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtwipdqkdy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtbpakkqzv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtfwmaqbuh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtiwiuivgs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtxxiheemn.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtqyaotpwz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtcsqhburx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtfulwyrfx.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtafbsafxm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtmdywekzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtfotayajy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtqbcudjds.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtmpznrcfv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gteebaplse.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtbqqyushu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnjbzxwr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtprgyukus.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtxzmjweir.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtyhrzcrjd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmycyrva.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtdroritre.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gttkoctriv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtkjuffsox.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtfpdknnvf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtnopxhajl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtjnwyeevu.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtdtywmamv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtslsboavp.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtylowscve.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtenohcici.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gthalihlmg.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtfbafmxwo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtzwplhqmd.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtwmsttgom.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyvvqbqw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfttcscpk.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtgtkbdrki.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrytlxdos.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtpoxrfwlc.html


<!-- 参考信息 -->