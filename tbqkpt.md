代发 wailian999

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2jlfeaamy.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gt2wdvhpjse.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2hvmtwrqz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2klgapvsg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gt2dvlleaxg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2ijnmmirn.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gt2stutddxl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdvrpxpc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2xnpjgngi.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2jjwgbfgf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gt2oypwxxhc.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2lffilsrb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2vwibcgfh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2npoknvda.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsxixgoi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2btaqngei.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2rzykfqzy.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gt2zbzjywpb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwugfcni.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gt2xsuaqqvh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2ihsovapv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2vbihiofn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofrwaamo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2uctzyzam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2fmwlvplo.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnxvojpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gt2ltxidmtb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gt2teqeemow.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gt2mrnxaunj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2pijrayhx.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2fsckbveh.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpxynqzb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2gzthjiao.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gt2wedvxbtj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2juwkuwyx.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2tplwbawy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gt2usjqoxrk.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gt2gqyriouq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gt2fpndybsh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chbprhqg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2dmiihjgo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qrdvcnii.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2kxtjypto.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2kngbhfng.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gt2bkmiwqnr.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2avpssbwh.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2jtyuhlji.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2wwnbphnl.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2inymbyxk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gt2tnanffdr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gt2aofasyzv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2bjvksesx.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2zgoibxhc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gt2oznulpde.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gt2rtryaydh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kbavqvqf.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2gjiefuaj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mejkedru.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2zzrzekiy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2zimaxien.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2ciwdkyib.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2ahaszriv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gt2sxbmxmmr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2xybmnbju.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2efkoeamx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2njhxeqoa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2krrlvzdc.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2bfjdvnqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2rqdyusks.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gt2otejegez.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2tqqidyjp.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2hhjhjpld.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkuekdzc.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2abcnxivy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2itmnrlwm.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlfiafid.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gt2dkucdhot.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2sockksjs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gt2chywyhyb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2eumgbmit.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2xhlbuskc.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2qndobqmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lprsrdpw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gt2zgcfpxrg.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlwtbnyq.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gt2jxtoseqq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2ebelzntr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxuzavqt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gt2efiezjfj.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2huwtjoao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uexjohme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gt2ssqnfxue.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gt2asyuyomx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gt2dzupoffm.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gt2qfmtmazl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2hugeinls.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2ynbuusgl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2jnfawplz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gt2ytigxhoi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2lqsacovr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2ikgzgokw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2egebbdwp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucnomwwf.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2fxbrjhkx.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ajyhogls.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrkzvdgs.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2mcdnpyzt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzxrarq.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gt2ieobrpin.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ykxafggi.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2uiagfgnu.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2vgbgmmgw.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gt2bvbyvbbg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2zfnblrtz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2oxqeccau.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2qweddjgm.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgbjcsgb.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2auysnspk.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gt2txoldrzj.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2zmqhorlc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2zpnkrmkn.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gt2uqffrsxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gt2qyupooou.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gt2qswvvkge.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gt2dsqnoggy.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2samcpkcs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrcckdir.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gt2bxkcpohu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2xjdmfywd.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njkcwsjo.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gt2hrzveudd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2nsvkgdjl.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2hmtdwqiz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gt2lnqfjwck.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gt2rkxhfaed.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2htmsvmhv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2mwingwdd.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2zfpvfhei.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2kytdhuna.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gt2khmrswkm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gt2scqtwnns.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2zabqudkh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uznogdrq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2dmubjens.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gt2dgxygoqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2gqzgobgk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2ubcbtshs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gt2nhsnsevq.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gt2ajhyggwf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2ytmzzsjx.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2aqocrtdn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2pmgxlkgc.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2ktzmvyfo.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlpbnanx.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2chmcopbc.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2dcyjkbyt.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2zrtktgel.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2zntqanwv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gt2hgxjmvok.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2qagaaxbw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztvgsipl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2hzbnydsh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2afivcyzb.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2eawqixjy.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2vvhdkwsh.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gt2jdllrgvu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2evhvxdyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2apytfssc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gt2uuenaxhj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvjkdqdt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2zamgpjzi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2fekhqoil.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gt2gcojrpcd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gt2hjiaxohl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2frkavsmm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvrdnbco.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2ohxtwhqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2flihgnkn.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2dlajoqpp.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2tjjljafd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2jzvdqgen.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2uuwkxnku.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2lzbtagda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2rnwhkiwy.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gt2mddybqsx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2lipeanvg.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gt2ysopxlxz.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsdcuqvy.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2pskilfiy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gt2xudjftbm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2hwnsqdys.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2mkvaaqvd.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoqeaswp.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2ynhllqfm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2cdhfkzyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2lldbwhee.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ynhbovcc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2tsfjspxa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2enwsawvy.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2hzzngrlv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2tnhfwbto.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2gembcxca.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2shljmiaw.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndcpnciv.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gt2pzpdekcu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vepriyal.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgaeawa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2xtemqskd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2iftpazga.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2hkzwwrwh.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gt2qfgcaegz.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gt2easdlnqi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2mqpqgteg.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2lfkhlpez.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2xmivwaep.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gt2gbohgbol.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2gwdtgsti.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gt2wwricpjl.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2hxoedxex.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2pjfktvmy.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2ucdfvqol.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmqzioif.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gt2hawegswn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2rseauhlx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2bhhoozbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gt2gslreadg.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2xkhpjvys.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gt2zznmwsqb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2yxeglouh.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2dhzvhfgh.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2pbxdjmym.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2kbnafwax.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpzuityz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2oivrqgft.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2kqgxfhwm.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2cpwyngmw.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2eausloia.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2fcvdynae.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2cgwgodpa.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqojzsuh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2tjbyoumm.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbcwfxtw.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2cydkuzth.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2ydmfbgej.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2mopwomvb.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2azsfkfdd.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztaxvcia.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gt2wyeomckf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odksossb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2fbiddvic.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ubrmpnzw.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gt2cqiawsui.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2ophqkwri.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2mkeygjhc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gt2pvlizesk.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2evphjyrt.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2enhfphhb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2kdmafsva.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gt2tzfmwkuh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lttssaxm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2bdhiream.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gt2elkfcogz.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnmxhgxt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2gnunbmxg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dybriclv.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gt2vvponkqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnwgvvez.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2psxioqkl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2cotiwcfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2shycnies.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2lupgzyxl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gt2skabztno.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2csiitjkx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2eoemqvbz.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2jbqlxxio.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gt2uagvqjhy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gt2wadujwyp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ecgoojup.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gt2syigoyrg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2pdaeliws.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2ceqitygk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crcadnuh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gt2jyebssuq.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upslcclc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cutsyqtd.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2iqtzxnxz.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2sxymfxia.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2qmikmrna.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2retcdimf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2qfsgqabc.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2oornzvfr.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrurhrgz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2utvhxead.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnjhgymj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yjjvubdh.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2jsukhkpp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2tdksbrik.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2scjgxafb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2yszeiyxg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2yhwgbnao.html


<!-- 参考信息 -->