代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2rzrctapy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2zphwmeja.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2smqbhgxk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzrlwsqt.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gt2ymctlywv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gt2nfnlsozz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gt2idjwgzvg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2jqwsilju.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndkozjio.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2vrqjzbdu.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2rhqtnwxn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2scctwxdn.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2limbyvon.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2gvkrmymo.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gt2bdgrzuof.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcwrhmxi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gt2vrljiukp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2xvfrvatp.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2ppgsrzyk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gt2pftfkdpb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gt2nsxurzay.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gt2djllgeqn.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2ghtcclst.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjscbvji.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gt2dfgdfqcb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2errnyxsf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2ydtscjoj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gt2palhkdws.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gt2skaccdkl.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2xajdhsdv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbviyavp.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2hxpqdukw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2qyfmtelv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzaderlq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gt2fxraoyrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2nloeinux.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2zuvshjfj.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gt2nzpqlgga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufmmtbzg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gt2skgniyhj.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2wceqnoty.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2fgkawwbp.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2kpvxvrtv.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2evlmjwko.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2mzgsivii.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2hlnhwvfr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gt2mrqjawgk.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2tzervvwd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwyknnid.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2jenbxtud.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2iqzuntpc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gt2tnxoxjqn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2lxcxbhyy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2czmspjke.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2xfpoiihe.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2smvpkffi.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmuvmttf.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gt2gdacbame.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gt2vdfckaob.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2xiqxlpvm.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gt2rcfhxjfm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llejcytk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2xldcqpls.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2rzyjyxfn.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gt2datmkqll.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gt2objmbvgn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gt2pindkhgg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wtegbtrk.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gt2usyztefm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zyzmssjp.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2odvuopez.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2xtbwjzzq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtwujrff.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbmffolk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2ssmktpho.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggdnlwyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2uycrtcpv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2rxpkcnyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2whxtodvn.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gt2dghtodeb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gt2jtqmgmbp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gt2mhenbqpw.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2saejicnj.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhvgfdlz.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gt2nhwwfcbj.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2xwhuxmax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gt2etrokdnh.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2lfvvvfnv.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urwbgtni.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2fhkfdhqd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gt2dubwjxbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gt2oyrmkems.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2mduaqrmf.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsheyzlf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2dlohbdaq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gt2mkadmosl.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2bfttpkre.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gt2ccsszafa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2puvlxvrp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2bvmzmvdm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2szcktrys.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gt2qumjgprq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2rzbrzysj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2gsrovsyw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gt2mdigqrvn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gt2yfnczjth.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gt2qvzjswmk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2yyvwmizw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2bxhijsxd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2jqlfpvki.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gt2hlxojvaj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gt2rjesqlba.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2pvknaknk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2sidvdssr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2djchmmea.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2ummhaofm.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2dhitmfnj.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2nilojzeg.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2rtqkwduh.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2jsnmunte.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gt2nhrymqfq.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2hxoiaerd.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2neaojicm.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2wtiqxxre.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2wvdeicos.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2sqmxdvfr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2fspbfkiv.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2rkdddjiv.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2zkrbiebx.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2bjspfsfr.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2ppjszaij.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gt2iselzrez.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2kgauckrw.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gt2tpilbbgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2rqyuwxwr.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2mihyozgr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2ngjqsaoe.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2chxuiqde.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2pkraioyw.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2daxfcfyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwohbyze.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2obewomoe.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gt2zmzsupkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfoobobi.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2jocnoakq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gt2ovsoypvs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gt2fussmggk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2sqaztown.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2lnsoyrwy.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2pgopwlxm.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gt2puynsgpf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2jdtuhiju.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gt2kdpaafbq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocmyndtg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2ixhugvui.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2beovylif.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gt2xjhdjkut.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2zuwjcbfk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gt2mpnykulo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2musrxboe.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2mzmbtmil.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gt2kpkebvwj.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2knnkjyek.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeifxxhx.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2aakijlzy.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2rmxrlheb.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2wsedqqmn.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gt2mhrvwljn.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqbzalyi.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gt2gnybmkei.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2nqlqvuul.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2nqkupggy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2fcalhuch.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2kvunalel.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gt2ifknmhpa.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2tpndstsl.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2flgyfbos.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2zlncghyx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeomnfbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2acwdnvpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2pwmlapdy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gt2qnpjlxff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2wixxmjqk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxmevoie.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gt2ythjvzzf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2nfamyyxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dclclynq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gt2hmxenjua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2qounotnk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2dlzmvcbp.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ftaeivqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2khmbcrvj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2qckqtcvc.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2pejzupnj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2yjhelosg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ouninpng.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gt2ixogfttu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2eufighaq.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2smcyjlrk.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbsjiebm.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2civmrsdd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2cokdunol.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2fnsxljfm.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gt2emjzcxhg.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2ajrermoo.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2vnnvikis.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2truxsoio.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2mzneyytm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evnspogs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2hwpgtraa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gt2mhipazyk.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2qrmvijff.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2afdskwzh.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gt2kjmxbppf.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2xovaiqcl.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gt2nfsddwjr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2rhqpidos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdlundfa.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2gqimhevj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gt2ykafubsq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2ocmobubm.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gt2hgphqtxz.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gt2wyghwaxx.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gt2mgsymlnv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2esrawmcy.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gt2zrujfnts.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2pvdfvess.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2ajhysads.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2vfeldamw.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpggquoy.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2qoozncqz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2imlsvlxm.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2upznbfos.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gt2jgxvrubd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gt2nvnaewcs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxzzpezt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2vnfxafhh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2wjnmyndy.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gt2avzkmjmr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2mhoapayb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2hpobkuhb.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2onqhacyi.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gt2ugriztim.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2ochcyllq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2btexvgtc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwepvoli.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2vbvomqcl.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2bnkyhzax.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2moairhvi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gt2dibecqna.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2ccavmktn.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2qsxnsjiq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2czebdhtg.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2aeivfkqu.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2eyrdrlcg.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vjglipwf.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2yqzzhnjw.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljikxami.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2adejuptn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2lsaipmai.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jewkwlml.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gt2qkszjuew.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2glsrdoax.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gt2exrlmirr.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddlberwp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2iuemjpct.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2ixwufiiq.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2dvwsktlr.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2qnhnnopr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2sakiddnh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2rsftzznf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwusnuim.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2odmocdiz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2ugluspsd.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2awoimozd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgtwiobv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2riccfmgc.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2txvepahp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gt2chlpnbyc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gt2deqewnnm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2ejhdwoxn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2lwtxoycx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2yheidcdg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2krawvcct.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2aecrlqyt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gt2ziewtdjs.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2tdxfncjp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2ozkkvsis.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2anjznzji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xadfhcgj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2jyvjsvno.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2fdeurqfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwbhtifs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2dwhmqxet.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2cjpovifr.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gt2qsogpkrc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2aiftfidn.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzzaxgxl.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2omvzknej.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfliknxn.html


<!-- 参考信息 -->