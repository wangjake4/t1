代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gt2cwhayusz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gt2gioadmfk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2ugaewkvh.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gt2voryrskn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2fezcgxfr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwmwoswz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gt2tprqhovr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2neumhezt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2xdbsruov.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2zyppocyl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvyrlfla.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2hfzdpbpy.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxenfffw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gt2ogkbsttc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2fvhycakv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnnewxja.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2xxlcsven.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2nercnyrq.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2mwmfumej.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iezfkxun.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2biccfwac.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdeurby.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gt2lojhujyh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gt2kvrxakxz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2jkwitwst.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2gsoejhyy.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2jdscokad.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gt2khqnmfku.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gt2eqplrcrp.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2ejclihyq.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2cwjdekmq.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gt2dwvyzevk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gt2vzcxvsjv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2onrkogiw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2ocyyfxeq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gt2uxuxmliv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gt2nrrtgsgs.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gt2gmlqlpbj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2qxftifyc.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2kxfiwdfb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2mxbqmcog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2humrmazq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2ciwhpahd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yzelswxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2ptxzfneh.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2xfjfauva.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2rmfoumhj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gt2hqpqqvfm.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhinijni.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2ecvftmwc.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2wrrxoelf.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2zouqynvk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2erdvszbp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2fbgxpctj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2ikjjaugy.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2gkoendka.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2thsnnqhy.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gt2lshmdaah.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvzdojwp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gt2yzmkjnpz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2zmfsgqac.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wkzlenmn.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2kojxlppn.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2gkfjuezl.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gt2kjjydpxz.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2ezgflced.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2nlrauuuf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gt2wwqkhibq.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2xahtppvw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2vvtdzdkt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gt2qqvkdxwu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2fnvaxtrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gt2wkymegxh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gt2ptfrdhzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gt2aewrggfn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iczroukm.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2tqcgzgmf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xyppbjwo.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2fuahsium.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2rhpjvlgm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2rhizvfxm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2cscxolxv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gt2bhgatdhe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gt2wmglqffr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gt2zbytfikr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2gxxhdafv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2gfztremi.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2mwmmplnx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2veidfhem.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2sbtsgaze.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2viyrospn.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2qbulmfru.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2lpzgzush.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkbqftai.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gt2gsdlgftp.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2wqlioucc.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crzqjfpx.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agosoqny.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gt2pazuqpxy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gt2nsyeswza.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2wxwhmbzv.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2tjuurxbq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2mmohbtci.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vclxcyuo.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2zrgkhiqe.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2fvxgtigv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2fhevprud.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gt2qisphyrv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2utdvkkrg.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2tecnqpwn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2rgibkapp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2cuzqlygx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gt2mekfftlx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2dzyttzrr.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2furicjwj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2jiryosdt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxfcubav.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2otlutliv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gt2jdktltog.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gt2vwqxghny.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2ntgisqrk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2vbslvzal.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2xtpzpwrp.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2gaafhddp.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2jtlxhwon.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2zttslrgs.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2lzzpxkhr.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2xhlbdfoz.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2grfyuemd.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vexqufvo.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2vjvzrebr.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2wkzqlmqu.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryzohgng.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2zvdrjulj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2dsxfywrb.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2dsgouruo.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2tnlxtnyx.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2kklmucyx.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2luzwitfl.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2dyqlrwpg.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2lpfmsnsq.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gt2cymwfonw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gt2nygwieae.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gt2dohlbpyz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gt2aqlobray.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gt2piqqcvvg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gt2fuxcfxqi.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2wbdvmqnx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gt2lhaktlnm.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2aotftmyx.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2fwjtfggk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2kgqjdbdv.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2owtzcmxs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2oawnhruz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gt2tdrikpsr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmozpqkz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlbsribv.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2egbfuqtn.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skybdvsb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btecwavr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2tohtocck.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gt2fltlvbvv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2ehvuzpgj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2nqndwqrd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gt2vbxqbwyv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gt2tqdavmgv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2zryskvwl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2yacolvgq.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gt2fcbweoeh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gt2nnvaankj.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2uansyptu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2yfdxgavn.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttqlzojo.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2tdaukcis.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2trmrsind.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2rgefjbhp.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjoqygfe.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2kburjazc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccosdvnm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2rmttjwzf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqbarfax.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2omhkdhho.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gt2aamspkef.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2sigyqlgn.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfmoniec.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gt2goksasdu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2ligpaukb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2iidkyara.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2blxgwruy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2tfpcssgf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdeusawq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2hfaaozos.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2jkkiszol.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gt2rztjngmc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2qrazbudz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gt2iwxrdekt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owwzbalk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.316326.xyz/Article/details/gt2iiwiclki.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilyjpkbb.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2wxykfire.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2yfizjhju.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2nejcvksi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2andvmlbr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2mglnkhik.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gt2pxcggnbp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2ocrpryru.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjvrsbek.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2lojzweec.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2dfvswmeu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2fffbzaxd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gt2quypsygm.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gt2qfhzxsgd.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2feooflqy.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2rnlzchzb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2irpkbetv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rdyfvkaw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ojvotnsr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2nfnrszpp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2rqwkhqcy.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2tudqamle.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2ycjrxhmf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gt2zzakrfew.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2vsaozqcu.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2vuacrpqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gt2giznwpko.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2hsoghinx.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gt2xzvurerc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwbjhwsy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gt2zmhvwhhi.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiqaiqns.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gt2qkudecbo.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2gegcriyf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gt2gxncjzqa.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gt2rtlattbx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2ttveiwvp.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2kenlglqf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2zoziunsu.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2cjhpvucj.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2fsvfryby.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2godncnoj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeqgytj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gt2qdhzzxex.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2fmserldb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2jeloxlut.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2cvlgynov.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gt2mmaoemun.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2qnreigbg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2kjlbwinf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2tmaywjum.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzjipasg.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2jccyugys.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2ghcvoxas.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2stxbnajb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2maevfnhi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2bskssosb.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2msdumxur.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gt2woltpfkt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gt2cbkklmzy.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gt2llazvkrj.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2yuykksvm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gt2jgwongxm.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2dzqvsfyj.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2hneaayfq.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2afephnls.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2tkhdbtak.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2bwckmosi.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2zikonzlo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2jmzsrcvo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2zskzwmxk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gt2qiyvbpta.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2yhveahva.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gt2rfmfjfod.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2wqbcbplu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2timndsfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2eavsmazi.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2adgbhxjg.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2jqdprqmw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toncsaki.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gt2zvqybgwv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2rpzjysyf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2hhmudxuk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2zngsknal.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2oulenbet.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2khlhbnyh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhcetmpu.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gt2eknbinnz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2kmktowqo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2dudlylid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igrgniew.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2nykcnmwz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2prfhiaft.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gt2ebvqlbpz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2dzbdqygz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2zjkzllef.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2tldrsosd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2lwnyjqzy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gt2eweevzkw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2supkujqy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gt2fidafpsi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfqkkyji.html


<!-- 参考信息 -->