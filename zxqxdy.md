代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2nhcqdtdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2sapxtlgv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2mpdnugxj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2gsafdvmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2qlqaghvh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gt2wdrdgrje.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2whkfyqay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2iasyvgux.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2cxjkcwyo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gt2ydlfxeka.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gt2pqqdxbxa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2rigjjnyd.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2eihfhfvo.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2birfpyne.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2obcqabpn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gt2hpvppbuy.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2xsnmaneq.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gt2hkfnshpw.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2hchwpqny.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gt2lwenyttm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2ictabgvi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2drvnguyv.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cujfromy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2ferzfhgg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ciosjpep.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sersfrsq.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2balbhgli.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2jgsdcjpg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gt2asmzyhco.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2pjorravl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vngqsxjl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2npcykfrb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gt2tageskee.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2jisbjydl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gt2koxergop.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gt2setjgflz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2jlmemnjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypgjdwbu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzaguzfr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2jqsupryt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqcpgwqi.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2wibvvdgz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2lyvrjkdy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gt2ugvbgput.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gt2travklha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gt2anwdpjus.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2xpwhibcg.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2icijlynm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gt2fxawtimh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmzrbzyg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nulaazrf.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2bnzivlav.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gt2cyamswkx.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2smwtgdow.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2uznonfii.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwmvbyi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2awircoke.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ehwajwzs.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2tgdwzdzf.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2yedfbghs.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2sgwhkwue.html

C#:   var (a, b) = pair;
来源：http://dali.havefunace.top/Article/details/gt2ydbvqopf.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2llhghtwr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2eeslpdxj.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivqdtdzi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gt2zchdpkil.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2cbflevdz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gt2snkowynd.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gt2gvzdkrua.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2wksbkoqe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivoiznbh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vefvjong.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gt2gmosnylu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2nwhudyyp.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gt2eizrgrbi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gt2oonrfqmz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gt2edwucbwo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2ydkehqji.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gt2upfvxhae.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2spkyqmop.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gt2kfvkoysq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2usouagvg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2irhxmqfr.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2tfpayrsd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gt2gvlfnhcx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2pkwwdift.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2qtiwmrxu.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2xryslwsu.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsmhzocv.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gt2ejdjbznm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2zmwgmwda.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2qrjsiyqp.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2tapkjwec.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2gmsrbcdi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gt2yvxyiqxh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzitsylz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2dtizyort.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2jwkzufqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmxodrhk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2jotwsipk.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2aggfwoyn.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2vfdigsds.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2jvfguxns.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2dpqoekij.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gt2rpyedmlm.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2oagrdvzq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2cpugjuho.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2hoyjfhzi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gt2jsdxmviy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2amiqwloy.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2myoxoygu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2bfehdtvj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2uasquony.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbplvmmd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gt2kxsmwxxl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gt2ydntrtov.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2njvfzqwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2cxzmpscw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2zsxsbnpl.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2soxvcdzq.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qlsmhsek.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2seqifdhb.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2ljdrvpxw.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2mxfnbtbb.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgjcfnsb.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2wozomtua.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2zoqmtgce.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2cfolacto.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2pzcqsgok.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2rdcktkob.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2dmrcsypk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjmtmed.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2ksrzhfqq.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2ocsopydv.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gt2lzfpqyhd.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2ocucdvwr.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2jppwystt.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2ipxyyrrl.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2wnptrggf.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gt2uvaoxgex.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2myvedzjf.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gt2utrphtin.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2dixtfzqx.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llvjqifp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2rghsakdd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qshovzzs.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytifnzfd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2bbgqxadw.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2cllchjvy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2lslgtrmc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gt2wmoydcyu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bibzntqn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2mkvkprsh.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuahxygu.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gt2uxufvtvu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2ioottolr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gt2khhymrwk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2rvcnrkmu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2fjliceis.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2tgxyajzh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2hzfvzifm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gt2ppuhthfy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gt2sdtbvopn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gt2lmafcolh.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2jrierecx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2opzoyvtk.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2hhbylrtr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gt2inchvtgg.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2vsrayfcd.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prrjocuq.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2wpvturjg.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gt2ezkoxuyi.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2gbmpmulo.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2zgxajcfg.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2stlektgv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2thxfoklg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2rjdogqja.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2retrtedi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2zlxlhcez.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2sdhpeens.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2szwbbzhe.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsusihrh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2uwpybsku.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2obgtmyta.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2dzixxmyg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2ekzducie.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2twimkjgr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gt2owwsstzp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2nofronlh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gt2qfoaiipr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcampxsv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gt2btyhiwot.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2kqlmxpbu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2xhwvdnpl.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmhmvisj.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzlnnjxa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2zsguybti.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2vyllsbci.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkxazygm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2jyiioqwl.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2ajiytdwn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gt2zamtcjpt.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2qeuelfzh.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2eixrahib.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2nmebakwz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2leuhluzj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gt2spjeruyy.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gt2svvipvup.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2psptqvhw.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2lwehnjtn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2jmsfmbuo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2gquujwya.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2kwaegibg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2mpeuwuid.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpapexhf.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2mvcjspzz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2fwoytpof.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2xxjebysl.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gt2qkqjnvjv.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gt2lwrdfkwt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gt2vxaspcns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imandxda.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbpzbtcu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gt2jcjdvuee.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vufxstft.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gt2jcxoxuay.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2sivztoxa.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2szvhtiga.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2jcectcql.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gt2asqnocif.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2sznuzeqa.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2dfmcmrld.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2ntygahjk.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gt2mrwxrjoe.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2sivreozj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aurgxrqk.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2trefnjjx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdcwfqzx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gt2kqwqwhkv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mamakshg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2gbbyemty.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gt2htcsmhrn.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gt2zkcpjbbw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gt2brbqojwg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2igktatfv.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2mtpdutbt.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hntrptjh.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2zognllil.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2kwkicczh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2ueppuhwk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gt2yvceopui.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2pzdqqwvp.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gt2wujhwdoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2wtptvqao.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gt2mtpbyuyu.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2zcimcjan.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gt2rqciexgg.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2nrrjtlrs.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2fcjeutza.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2nucjktoa.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2kwytrwcc.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcjqcvuq.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2wuiubmqp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdekgavu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2qzoiazic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzquaugy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wegnuxfd.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2rrwtusdr.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2cdcqzbkm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2ojitylci.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gt2syfgkbpa.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2ntgdlyth.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gt2nvksmdvk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2speucbtm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2npxmrzzs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2plzadota.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2hifckjou.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gt2lzvqjqhx.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2jjpmgbzu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gt2ybngkafo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2xyxqmigz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2wgkqkvpa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vehmwauu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2chahxjje.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2dubqoovb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2tkwauvur.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2anyzacrp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gt2amdlffbh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2ckkyizrp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gt2bxgwxsmn.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gt2ieuxqwjq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2pmdctexr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2qoyhepbb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2yevryfzj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gt2qefuprbr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2uycvfuwj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2gxuglrin.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gt2khucvwin.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2lvapztjk.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gt2ylphlbyh.html


<!-- 参考信息 -->