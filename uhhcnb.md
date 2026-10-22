代发 wailian999

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2rvklinkg.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2xozvlqra.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gt2xhvbzvre.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gt2mmgohwbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2yraltkua.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gt2exlucldc.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2exbfrhau.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gt2mgmsdigq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyyumtyl.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2lvbunlsm.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2sojjysze.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gt2kkmhjmbi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gt2wzlyagfr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2msckcyct.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2dycwttpl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2lotsdnpz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcqxjyib.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gt2mmgeegpp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gt2fryosrnf.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gt2nemudrac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gt2qrcxxyhz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2shlqspvx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtroibmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2gxguhkax.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drnlhtvp.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2zmejihhp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2njigmhdu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2byivxycv.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gt2rbjcjufj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2kzqfrsnc.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2rfnvptgk.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aglyrvez.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gt2fcckcary.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2uuzcavls.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2hfyhxdev.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2pkjatpci.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gt2oxopwwyo.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gt2waqknecp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2cacpdfnw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2tvwflney.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2xvwznfwe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rqbhhxph.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2tzsdyczv.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gt2ahkjfocw.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gt2liyagujk.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gt2zrzorosb.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gt2qfnmkedj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2jokbsaya.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gt2ququcbvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2alwbmqqg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2jsoywtli.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kfoogvjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2bnjnolgt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2qntshwgc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvggevzg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yscixnyn.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gt2bqazgtxv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rddifyoi.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2nsunnlgy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2qdpyifxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2cdljnjsk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2pdsqtrik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2immwjhat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gt2xttryyvq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qltoddal.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2wypvwmjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2llfrlkyb.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gt2ltkrztuc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gt2eydarcvn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2dpirieha.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gt2plnfuslv.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2taxvjwxu.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2kcqwxaud.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2ntxgvnqs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gt2vgmssrwl.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2mnfczkfv.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2kygvdffy.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2smecftqq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2tlgiqpkv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gt2gwvzlkcw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2sirfxmon.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytodvjhk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gt2cjxuukhn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gt2abdhnavg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2rqpvpgxu.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gt2ftengsoo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqtxjknr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gt2pjhasgli.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2lynqqbip.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgzhqlnu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gt2hvriwuuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gt2iicgevpz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2asgjbvfl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hafeuwcs.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2afncpvte.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2tqdkkivi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2uoannvwi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2pqwzvcnb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gt2cctqtrgd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gt2dmnywnns.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdzfchno.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfgmloay.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2duafcqjx.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2fccrhgnf.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2fuolkvqn.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ujsdykbv.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2egzcmgwn.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2sgqqgtrq.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gt2jqqfjfej.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2bjpnmdka.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2kixvljja.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2qhvqmuls.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2glwdeiva.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2kzqebpct.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2dueelqzx.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2uqhnxixw.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2gvmcrjkd.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2jihazkrt.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gt2gtlnivgq.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smaztmuk.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2jybzqerj.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2krrxbbpr.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gt2nizjvepw.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2ymdfprwk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpkllljg.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbaovfyf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2spspaour.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gt2hdfbfrue.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2hfugkhqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gt2bztikaky.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tstsewlh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2laarwgil.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2pfyjwfyz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2hvrgdago.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gt2udneaive.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gt2pqzmvmct.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsnklazc.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2oqtsgycb.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gt2kmmehirr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2mpeyzjzi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2lwjmgjnx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grknldfj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvzjhtbk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2oinvwpow.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkznzayb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gt2lbvorokn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2wupiqrgq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2syvhmvcs.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2jmrydpvf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxhcccur.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jagtemff.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gt2ausycqul.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2xqhaywfa.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gt2oarfylcd.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2bbtrqavu.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2cmxcmrtp.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2byqspxaq.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2vxtgvhjw.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2gmyiviqg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2fmrqbvxw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2kbgcplfi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2duyyphyl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gt2mteurevt.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2tpzulrpo.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2cpdojuds.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toppauhv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2lholrfdh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2lmijoxxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2yctalkyz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgofhdsk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2ictpaktj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2vhzznwdx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gt2vtzasyqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2cwqnfavx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmrmiljg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpqdpyhr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gt2fuxiwdkk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2mehuimkt.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2aaiphadd.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2clbknufh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2mdzspfdv.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2yqgffwcv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2wlvtojwx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gt2ovjkntbo.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2hggjsoir.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2nogajuzx.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ckjcuwnp.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2vjozrxyo.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2gqdrtsix.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2zkezcjtl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hztqfodo.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2kgedjfoe.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gt2xdeayuml.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2tomtmzct.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxtpmtqt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2eiwttgoj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2gqehoapf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2nyqivsee.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gt2fgnrmbhw.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2qnltgvru.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gt2yfbbofnw.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tigiqses.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2rjjylidq.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2aiohsbmd.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2sknwwqfg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gt2lwtzcakr.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2uahozjio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2sugnazsi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2ctaxhlzs.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gt2ctctlcfs.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbglwppz.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gt2dnaznlor.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gt2rqcmopqf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdgzbqix.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2axvdtbty.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gt2kcjgibeb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2pbsianyr.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrahzgzb.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2nozehwuc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2diezvhtb.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrffelxd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2malndnjb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gt2gsfgrefw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gt2xjzjirho.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2rikzpjbt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2keoukgfm.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2qstemxhi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gt2utonzzgu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2iimppjcx.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2sepydlji.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2bfdsrmmh.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2lixctoyf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuuezqqd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2cqdrjhre.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2cfwdokhy.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2biwypzst.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2gvqflhfo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gt2peeikfgd.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpriertr.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gt2ugzzmygn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtqvdwfy.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtencltr.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2sikrhjzw.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2wsurfock.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2vjholugs.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2kppziypd.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2awcdmykp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2uqxenmug.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2jbcwhuca.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2ewtshjnt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2wbfoybib.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2hhentwjx.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gt2fwtnzujt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwhuelkl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gt2jilpkekd.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gt2yeqrbqzz.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gt2vapkfjmx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2lezcuulu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2dlhrbjbt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2rvoqwzcw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2dvacgome.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2ntfxenuq.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2vzubjinq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gt2njfoqajs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2amljgpje.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2hzbzagtn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2nkefupfe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2rtsakeyz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2dszcyrtq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2xnvjpvad.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2thhbqkxg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gt2toghbhxa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwwdodrn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2gpcmhidc.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2vhigcees.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2meazcjux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2vikerpha.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ivdtzerh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gt2bxlnyqev.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzjaxhuq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.kuanghao11.cn/Article/details/gt2vvyxvoer.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gt2kemdqyfc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kjgqthel.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ttygwhok.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2embcppni.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ljtoggjo.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2dlufjqaf.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2nvbqkjxo.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2nfoacfgg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2gnfgtybo.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2qfqriakq.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2ofvyafma.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zyzeoski.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gt2prrypfbl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2luqnghfu.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aognluks.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqdgwxxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2nzzgxakq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnmbkvyu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2ryfrimbu.html


<!-- 参考信息 -->