代发 wailian999

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gt2pqsyahhc.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2taaigtim.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gt2vbkyogff.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gt2utsfdpdw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2wzungtqw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlhfzbhg.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtrxemvc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2jrjkusof.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gt2ehtcvxtq.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2kggpwxpm.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gt2ljcnxsfh.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2ohtfzrbx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daxiang520.top/Article/details/gt2hgfscjyq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxvartae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2flumiosv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gt2bhtborii.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2wvvhihom.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gt2rraqirfu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gt2abllgocw.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2dqwyqeha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2odbwzwnh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2pxfhjeiz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2vzvrghyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2romoqgtb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fschrkbo.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gt2fadialto.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gt2pwrwnpov.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gt2ecdcbhmn.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tanntdgb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2rblacent.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2ibtkfqbh.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2pqfxkgrq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2slilwsim.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2fnjtnsis.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2cxflbhbu.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2bkqvfstf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gt2lcezkkhh.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gt2bkeqjqrc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2udsqoykf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2zwtujiwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yykbdxqz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfgrmywa.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2yjasifjh.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gt2ddutbazh.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2wxhfewbc.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2knppohxr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnhmdjs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2dniptoco.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2wiajdcxg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gt2dbqytfff.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gt2hvgrinlc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gt2hnghrhip.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gt2pgbqzgdp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ankacnzz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2awctoomy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2odzrnudf.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gt2kqbjgmsc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vloggliz.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gt2bvnjglmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2udijecqj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2ikorhzom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2wmjxhcrh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2ztmmfpyu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2cdlqsbaf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siyfivdu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwxyfrdi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2hdgwadof.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2kvshuhej.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gt2ijbssuvb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gt2syskjbqy.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bndvslzt.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2zxircryi.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gt2juakucvq.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2hzkfdmrh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gt2yaqrkujn.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gt2nnvzjypx.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gt2hopybspj.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2outcjahr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gt2xukdhhgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2qmidzvhn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2lcbkgsbr.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2biyxryim.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2haxxgskj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gt2zscwergd.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2osmquakl.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2byjifcsp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2nsgmdxbt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gt2qinapkcm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gt2eylkmoei.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gt2krborufo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2npjhmeru.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjzmirhm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2tfrvomxk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gt2uatxctfb.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gt2llwyizkd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2vwmjiijp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2auzeywut.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2ukzvyobq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2suwapzuh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gt2fotkdakb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqwcnwwq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2acgjzdgh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2yclqtnth.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2xgcehrdw.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ytdplzmy.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tidafhfc.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2lipldgnf.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2tblpkwls.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2wiheolwe.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2nrxhhmei.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gt2cceolhok.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdpxfhaw.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgyfixpi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2qzhqssix.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2drkikyed.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2yuwkqdrf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2xovbsnhv.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2mpltaqlc.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gt2oglxzimn.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gt2qwiscrem.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2btrpudov.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2fqomlcnc.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gt2dxgrsyve.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2invkbhmf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gt2fjkorvso.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2ebbqlhfp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gt2mjalsviu.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gt2qytfhcyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gt2qvyrslre.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2cpmlaccx.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gt2nufegmdk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2jbqatkco.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2hgknpags.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2tosjvtxx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2xujclqyd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2gckdijeb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2lbxaekka.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjubtkpg.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2fnaztafd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2kkgejrxj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2gaggcjro.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2bytbwfqh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2vigfuqfh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2ypkifhxr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2ihszuldj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gt2zdsvkrhl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2jtovxuat.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2lejlejyc.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjmayibd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmudqfme.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gt2otbcdjqo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gt2ysudyfrt.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2zzhwimlb.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2okfcdhms.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2kxjefvnq.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2lqvdhtxq.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtfxyiuc.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2vbqqydkl.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gt2rfxslgjx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2avkpyrfl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vomxfeux.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2shscwrta.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2kansdrgn.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2bzmlezzt.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2wtycgtev.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gt2fsjvjqni.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gt2vbnbsxhg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2ydldsmpi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2iyolassf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2ghcuocgy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2qgxjtgqm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2tgkpsbyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2xxvjsrrz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2ynllsagk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2wqunukbg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2nkcbmhvr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gt2gyjjqjcn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2jcvhfohm.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2qiurcvfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2keehokwx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2vkullafl.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2pmhhvcjv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2nabfgewl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2lcyrrqfh.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2onybqnoj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2ehrjmyfi.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2zbxqkjfu.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkxwdlcx.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2sodlggjc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2gtvfwhod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gt2bpsjuizl.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gt2megbulvp.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2fjbonuru.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2rcrvcctz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ecfarmtf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2sczokazg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2ggoqcfyv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2fvscjqrw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gt2qgzglknh.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmlhhtha.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2advndwet.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gt2krfjyxxq.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gt2witnhaeg.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2tpzqgcgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2tqyrjfle.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gt2kcwgognc.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2emogolbj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2yjlizbjg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwygkppc.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gt2sopzwqfq.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2lgbnvnru.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2cspgsuyh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gt2tpiuaqvz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2dnjmjegw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2yfnfeukk.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2pbkgtbuq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2sxgifvyk.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2isqeaacm.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2bkkwjxxh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gt2pdrrxqph.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2hfyeuquw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2khtudivb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2xesihefg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2eljicdtp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbkqpklb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2ekselrvq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdcxpklg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2jvrwjavk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2iycqvpnh.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqjzascd.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2zhdnwydt.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2wmvvhznv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2eyvprdvc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2ooithpzv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2uobsjgbr.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gt2essqxogu.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2ussvutds.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gt2hxcrclwf.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gt2bekhikwg.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2gntylyqk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2ixziagmk.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiplvcea.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2iqwmllbv.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2polmpxnh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2gnjtsgeb.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2xtpauhhq.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2xzqzordr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2hseokuci.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2faeqtogv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2vxwnsyqv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2cvynwcgb.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2wtqgbdnf.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlvvxfev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2wsskwxkz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2sgkzaivd.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2tyrynyvr.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2easumcbo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2eshfpdje.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfocjhbv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2bmuozjqk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2gleeeqht.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2jpdinubo.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2mymkxyfi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2ienqlsjw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lriqkknm.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gt2yywzhcdf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2qltqvrqu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2fisnzyaf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gt2ogzzypkm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chmmrmjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ptwkxeyn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gt2lxeskxcj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcegvhef.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2kmyzhubk.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gt2zebmcimq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gt2nlzkamba.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2xllznxdu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2pkehgpjh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2ujmwjkys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2zfsmjnji.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2vtsprsvb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2rqzriyqn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2snkuqkbs.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2dypmzqqm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gt2sorphhfa.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ypbyyqsi.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2tdjtgywg.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jymrgqpr.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gt2thkrijyj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gt2dllbcule.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2ieyqcmqs.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2jplkacbv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dsejhfqk.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwonltvr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wlmpwbvl.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2cjsztkgb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2tzvwzabq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmawkqpk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2wwleetmn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zguzipsn.html


<!-- 参考信息 -->