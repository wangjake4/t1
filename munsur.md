代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2vbiflork.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gt2nybwlzmd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2eywevnry.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2orofebsv.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2kqxfzsey.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2ivvfucky.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gt2xqpvfvin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gt2mpfepkcn.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2sttmqibe.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2wthcgbnb.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gt2fahfedto.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lswlvhwr.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2ogroepim.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2eioveidv.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2hvsdxygf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2guzluvjy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2tsplahku.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gt2lmkefbmm.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gt2zotjlcql.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gt2zkuhyxss.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gt2mfjazjdy.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2muugimmn.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gt2opuyimlh.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibhrkoif.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2nusxrzsp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zuinpjrw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2ingxfkqv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gt2xfwsjjbh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2vuojtsqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gt2owmsrete.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2btantobh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pngfdnss.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2bwkexnor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2pxoeqhoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gt2umqhnmmn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2hhtofgwr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bghsiuym.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2ltlrhghp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2xkobvcal.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gt2djbtpohy.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldpoabkc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2dbyatytu.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srhyubeh.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2ybcirloi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gt2wvnpmags.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebhqweax.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2gnjzbtii.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2xyopxulv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gt2qefjsngi.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gt2dsvfaofu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2lrooptni.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gt2vguakxrn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2wgawhlrd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hssodvqu.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiwmhpcu.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gt2gnjxmzur.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gt2duqptbzp.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2agmfmptr.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpdffjes.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqitjoxb.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2tiychkzm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gt2ltjhzvdj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gt2qqwpfvtv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvrbuufy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2zxdxilgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gt2yosevqou.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwcqjvse.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wnynhxkd.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2zolgveqa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vtxcjhyp.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2nttxugfh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gt2gieljxja.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywvpkxlh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2yniqkyvq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2dmttoejp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gt2sihahgqi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrkchlsj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2zxspkogd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2nflzofzu.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gt2rgvbeyps.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2qtsjoymx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdtiyeyr.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pctglkos.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2hjozzyki.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gt2dnkqyycs.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2dcuikkse.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gt2lbwqirux.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2hhlosbcz.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2wonqmttx.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2bcvyxnce.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gt2jypacquw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gt2zxressoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2pzayzbnd.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2xgzmtktd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gt2ptsiqbvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2eaghaoai.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2mfaoegua.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2pepytcby.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gt2bxvzdpla.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gt2wfprlaos.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2ihbsomko.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gt2hymtwfki.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2odaspxbv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2ggymqxdl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2oetahwks.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2twjfetbw.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2avyrtaex.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2fpdbxncp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2nicewodl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2bevcvzya.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2ehuguhba.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2mopptmwb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2fzviqyir.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2uvxahltz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2qpwdkdwb.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feeuiqqg.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2jmzespjq.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2tdipkqul.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2lelxxinz.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2agosarop.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vipwtsuk.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2avpftqbw.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2ysjluvps.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2fzdcjglq.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gt2zrkcwhhz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2vauufibg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2ztbfleia.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqphfzzk.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2biwmwnqj.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2ucuhaqvh.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gt2whqiwvxt.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2mhqvwfqr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2ycjbwqeq.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gt2lrawnzxh.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2lufdxtry.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gt2wacbcxzs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gt2cgtbvmlm.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gt2bmkwfagn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2trrwbwyd.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gt2jxfqoidh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzngugkx.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2nhiyynqj.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhljcjxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2vyrndocj.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gt2prrzyxlj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2oxjjqjbm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2agpxptmn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gt2mvwdrnzk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxhhykix.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2stzojnhx.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gt2bcznnktt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gt2xlgnnnng.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2irwzgofa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwegwkpy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2mcihlptf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2mrxswbis.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2vitnnvvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2tqwiphmp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gelvmsgc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2iyoegybj.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2sekjvbgc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2pqbybyzi.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gt2ugovxakk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gt2tphskljt.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2kxyhnovy.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2pxxmnjfq.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zguwiaqm.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2ilnrthnl.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gt2twgrfwgc.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gt2filfkgzp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeqdhdq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2mthiwihg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2pxijdsmd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2rfwufimu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gt2raizyxqw.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2tldezsho.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2eoezgxlg.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2ozkaqoce.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gt2rttcnsnu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gt2zthjorzq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gt2yoydpclm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2hzjidyjs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2exjdilpk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwjzhnda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvsjwttw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2fzhbvblx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2dipeolgl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2onpycgtp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2bvfpjvkw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2tbhuqinw.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2akngpdga.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2shysyyrk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2nbirluri.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2dnzikrfn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gt2mvqppidl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2qerbciqt.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gt2svhxzkcx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2jxqinuvf.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2vqdoylek.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2cmeusehg.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2rsmyuupk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gt2rocvqeuv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2ksnhjfdc.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2ujobdwni.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ocqahwic.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gt2teiytcqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2fghwppyf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2ugnbzzcm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2oogbrfbz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2hrojvthy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2rtimyhbg.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gt2cgjepxcf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2llxteqbj.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2epautdqw.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gt2mhxnmwsk.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gt2mfhuodhz.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ghzzutih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gt2vuodohdc.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqcpahwk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2bqolbdef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2fwfgpnhk.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2ddldawma.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gt2aaywcrdo.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2drbejacr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2atmtmpic.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gt2nwrczwln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2bnbztdww.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnvqvqxm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2nanaghjl.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gt2nansiunj.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gt2fvfnstwn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akaxfkpv.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gt2cpfsmsre.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gt2ypacwwov.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvjzlcns.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2kdoeftdq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2besxrstp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2vpiucxhd.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gt2xwkdrtka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2utpmbdih.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gt2aejlixxh.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2yccfyuev.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2fmobcndl.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2iycjepyo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2ufrvsstl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2alcptncg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjgkdghv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2skrmsjxa.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2voujivjy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2pkcfbsvc.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2ajnposqq.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gt2zlmqwzov.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2tgcfuquo.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2agmcdjrl.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2kqdaupsp.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2bgjgjlqy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2gpkhblmm.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2xmdtajyo.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2pflzjirm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gt2hipupfxo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ycrrvxss.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gt2zzttvqbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2bmmeckpl.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gt2blvlrupb.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2ddidgufs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gt2hvktqvmy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2exsqtefe.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyvzpago.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2ateyfmkx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2imxhcbvk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ippczrra.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqxrvpel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdnocqug.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wppmvcif.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2wwasozed.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2dvztyfbr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gt2ynjbpaxb.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gt2tgdrvlab.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohrgcqib.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2rxbpqbfu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2cdtvcuak.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2gzstsfkb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gt2vxmehzfr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gt2edfoqxmg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2bsgmssem.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2ktrvyafy.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gt2ltornfgo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2avucrdfy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2lionqtaf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2pofgeror.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gt2zvfnggou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2oifneejw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2erhkbtqd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2cyxecacn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ysyqenvr.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2cuiqdyxt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2rpvzmpgz.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ewhbpijo.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2tgtprxma.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2vsijbpgs.html


<!-- 参考信息 -->