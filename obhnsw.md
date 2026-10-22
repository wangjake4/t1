代发 wailian999

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gt2ksfwrhca.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gt2xslxcjaf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gt2wrwnsesh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gt2hloyrzpa.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gt2rjsretar.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2mqjnjgjw.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccdabzed.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2cecxrrhr.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2ujgmrwxe.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2otwbsibh.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gt2roumnoko.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2gtqcmflx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2sddfmrax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfkzjxfn.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gt2ksnadsdv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2gsqtdshx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gt2akgswvdq.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gt2ujzebvfj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gt2bqzoztdt.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gt2bfumcqar.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2twearpym.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2cioxjwpq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2wsinjwvr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2fiqplita.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2qvgfxleu.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gt2rovlqtem.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gt2gfqrhgkd.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbdtcbjz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2asclcxdh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2xwycqnah.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gt2hfvsclex.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2hofapmxr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtwhsurl.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gt2bkuoiiky.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2qijsxurf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zapsklpo.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2iugoegll.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gt2mzcaftip.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2baqjuqei.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2vrzqwrbz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2tcpzljsx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngdlkjgz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gt2yexoxgbn.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2ezfenous.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2qncvnmnj.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gt2rhrujgur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2cungmtgo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzlmnobm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2loyxufnw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hphhjlxf.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2svpqhkeb.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2lvoocvpi.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gt2axtvjaup.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybhapqye.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwiulzpn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2sllqketk.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2dfcwdyro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gt2kdyhzvmf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2jdvhtohm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsmucfth.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2latddoyv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yndgvazb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wnpkfhen.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wzajllhh.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2lbrrhhse.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2quwzlvbf.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gt2tdjeiksw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2guitlukt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2iapozvby.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2azmbwivp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gt2qycgzavs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2hmwtmfwh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gt2txwrhqru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2uzhqptdq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2gqclbhvu.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2lhhgptpm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gt2fqcunhbd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2mqovojcv.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2zfjbcxcg.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2flviutkl.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gt2erllciey.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gt2pkhcqldt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gt2ncurzbyf.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2tsyhwzul.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2jncddjmi.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2syxtzawr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2ulbduruc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gt2ulgikbid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2nhxwntbk.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2oftsurld.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojlrcrfx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umihclpc.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2beronlbz.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2zdkmenys.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yibpvbhc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2lgbpcfgz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlrpvypk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqyqsjk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iiirgusc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gt2gtwzjfxj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gt2pbpzkine.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gt2whnclqdo.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gt2vhyjqhfq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2unfsntle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2oojdzzcl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvwhpqyy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2yqovgkka.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfswovnv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2sgwachgr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2uuhgckbd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfufjuff.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2faelltzj.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2eglhxcqs.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2swbsbfyp.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2dgkcjgfu.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2bdcmkzpr.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2phduamvr.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivglluan.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2fqhbesgk.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gt2cgmzqdlb.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2tgaimuwl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2pwppympb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2vrvjongv.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2pzlovhec.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdcghirv.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2opxcpqbw.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2nrjxaaru.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gt2jsesrffb.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2gwswaqvl.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2smibhhkw.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2pidsjsmq.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gt2hoqtcays.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvajteep.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2vmsqzrob.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gt2dliracpy.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2ekilwhws.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2eyriiraa.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nclgxvbf.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2wzfpefux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2lwdaovpq.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2ohehykcj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gt2ottshusv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gt2avkzombi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmgbqsmm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ntmkufcn.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2kzbqvaco.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2lhxjxpmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2aldxaixf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gt2mmlaxyle.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2vpxyeehu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2fwpzgckl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2bmnepinx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2oxiooddm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gt2idowyboe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2uitbweun.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2lbdnjapq.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2mkgeuhpk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adqsxmrw.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gt2xjnwppqz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gt2ogfcsmjx.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gt2atgtilox.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gt2zrwkkdel.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2ybpfwlil.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gt2cmstarak.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gt2hwmkyzfw.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2nvcxqrdv.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2wiiwcvsn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2jiiukxpw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2gbllruec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2mddilrls.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2ckuhvjwa.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2vxxeboqx.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gt2zkojgnsz.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2nvhwcwra.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2shmlwlkc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2qmayzsog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2qwcfaoby.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2urvztudw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2ebrpwzrv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2sfgguxam.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gt2gmfdfjjm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2cojeecjj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2emfxecyc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gt2bqxluiri.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2yoklsxes.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2vmicgipv.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2oyabvuro.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2xgpnagcr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2fjxeifjk.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2awcqpcof.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2gdyamfmf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2gkrcqlah.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2tlfttgie.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2bropahzt.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gt2kfpuijpj.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2bfxpxrlk.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2lbdoxksk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2oogxjlvu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2qchwnxap.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gt2ylvlqzyv.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2yqcpexif.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2vtstorew.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2ysrvyloj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftetbqde.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2cblqnwug.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2mzrsixil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxuxmvxq.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gt2ybhyftbt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2lbstvcmw.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2jngclutp.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2wnwrpazk.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2dyhctbtm.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gt2sokdikrk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2txmbqnuj.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2qzxrxryz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhbamqra.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ouinprjd.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2erchrwow.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2chrfmzbt.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2iehiziny.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2kvgkxdkz.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2yomnczan.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2huqljqtm.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2xbddckvx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2jtflmbum.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gt2bgadiqrt.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2omdnhozs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2jdrvejvk.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baejmbpl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2zicexxtu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2bakolvcx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2oodgjyba.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2eobhlwbg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2pdwtmhgl.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2sjvzaoab.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gt2lpqhbvdm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2xgawmzap.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2rguapfuh.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qguxpcgy.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gt2kipelhus.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2qwddmfcw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmpwtgwc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gt2qgwqcnem.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxxtpvuj.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2xxrkxdxe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2dqnonuek.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2avaapqgt.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2kjufisrm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2pudjexcj.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2awwwzhqw.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2lglmmfpb.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ukfqszdh.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eepczymu.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dhbhgipt.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2jorfgefp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gt2lxnqhbcq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2lamswqgp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gt2bqbgpxom.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2sipvtnaz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wionudkf.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2tnqferkn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2svaqhday.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqpvukyn.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2gmudtnic.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gt2xinckyzj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gt2fglkjroy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgcdhpwa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2dfpkyaam.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2bprmqloq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gt2ngeifmsh.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2ocyyccad.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2jzwnkpwf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2sfwnbext.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2zxmrifoh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2tsxblfhd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2obddskcz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2fjhvwtdo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbbsqpgn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2osnfuwmk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2mjhnnwuu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gt2lcpubkki.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gt2kxdvxeqp.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gt2dcjfieof.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2xmufqkxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gt2qokxuekq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gt2czymfvdh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gt2rcwkokeo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2awqdvvwz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gt2iipafsug.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2knylbfae.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2yqivztfk.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2yuhukqps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2ngyttcis.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2fwxbvqfh.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2xrmvmmje.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwmhncgv.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2jggrakpi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndsdphlp.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2bociixnv.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgglheia.html


<!-- 参考信息 -->