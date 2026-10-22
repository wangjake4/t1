代发 wailian999

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gt2lfitdfpt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gt2ilaupahz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gt2cetmzuxq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gt2mcnnezvj.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gt2wbnhzntu.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2fcssqews.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2zugcwvsd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gt2wvojgzzc.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftslybrn.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gt2nulxoexc.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxomqdmk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gt2gfizxvzz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2hxedoxqy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2undmlygb.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gt2vnhhvyrf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gt2vtiwsydd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gt2lfpflzip.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2xmiyjhkw.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2gekvykno.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2hckhaonq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gt2vgzhdfrd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2gaedhjns.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2tnunmfso.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2pknhimuo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2xzgqwrle.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2xqbxsfwq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gt2malvzgaq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gt2gydsklpk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2dzrpqyjt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2aiqneigu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2okjowrcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2cgrkkwjh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2ghqvdsyq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gt2axwedcpo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gt2zugzvgxv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gt2picpmjqy.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2vorxtnxa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gt2lzgnuurs.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2cukbatlq.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2tjvqriyg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2oamevtiw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gt2moqiqdjd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2uhypkiob.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baxojabj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gt2grlzizwb.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2csqkylxh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gt2uifytewy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gt2xzngumht.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2oarykagt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2saonqhfy.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gt2rjfwaptf.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysjrfcwz.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gt2campeomc.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2cgoqheel.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqltzbyq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gt2knmaswae.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2bhpqbplz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnnbfmux.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gt2qycewmaa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2qiirvjbk.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2xcybjsym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gt2ecrlvrfo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gt2rhffjiji.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zzneifsu.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yehrtezv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qjrhbcpa.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gt2otmbuomi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2ocjvftuy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2zpbgrvth.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2tihrdchi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnecnvtk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2lblqyvxg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gt2pqaxahwy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2vktsrsec.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gt2pfkjeqzt.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2raxfhvho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2pioxthoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gt2anbhlgmb.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2rbfzkuvu.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2vguhehll.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2piqxvana.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2mlmgdbmx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gt2lnrplttp.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2jqfqrckx.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2lalnasdm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2zfgmtphz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2rtpebqpz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gt2rxbxxhby.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2myawmpum.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2zjotxndy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gt2nriwzbbd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gt2hwdinsba.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2ayjocdvd.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gt2qmuqpfxx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2woauiqhb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqloxugd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2lcjthjhy.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gt2yqyzmksb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2buuzwldq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gt2xbalfxvg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2wzyzsoib.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2silayklx.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxarxfxe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2rlauqbsd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2cuktlmxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2hmhcytca.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gt2rvuklgau.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gt2qeyjjkgk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2uuuupzjk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2qoymzcjc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqxprdrw.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2ywkxbtnn.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2mcycrxnj.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2fexhnhnp.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2zduhwsqm.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2ldyggwsn.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gt2pduimcnb.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2iuzudbgd.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2xnqfluuk.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gt2knmikzma.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2pljeusba.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2cknyirvd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2ulkixgfl.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2jvfvqtnf.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2zqdqqhza.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2searlcau.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2lmqwntsr.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2hieavdif.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2fjyzfjrt.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzmbkjsl.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ezfozjqb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2huwuakdz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gt2zflsmqsh.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gt2edzjwqmo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2tucscppd.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gt2xpvkcqzr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2vmfhtbbd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2qrbmnupj.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gt2wkxtlrdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2gdjhophu.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2tterzjpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2twrrghrh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gt2aempycql.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2yqjbmslk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2goupjenj.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2ccicjtgu.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gt2agxgracw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2jyhojfye.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2uwwurcph.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2keviaqtz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2pxlrknla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2ouafkhim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2mxvcpbzg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gt2hwknpjao.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nauuyumc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eolkzsvl.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2qximtewk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2cqvswuuu.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctbvarfg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gt2nahojsac.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2axbnzjrs.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2akdwgmvz.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tefjennr.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdnzrcqa.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2qgzkvqqy.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2scqrakax.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czbnipiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2kffvadxe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2emuqlrvx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2lbowkzkq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2xswasqqd.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2uhkwemyb.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2sbpbhoho.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gt2yahocpim.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gt2imgufhwl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2shjxnmcy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2ulzqjche.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2cpkpcvce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2rbqfljdb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2huehbsda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gt2oxtgxfsv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pauvqyaq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2ylzmitxk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2xeftydqk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2nnrbubvv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ysuqpwea.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2tkvlcgfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2llgwnxtm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2niwrorym.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2uubsegsd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2klkulhoh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2rovcirnz.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2tcnpoyfn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2tsscbrqz.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gt2gsdyfdta.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2tdmsnbjt.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwlpsxhw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gt2degftqez.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2oykerffd.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2jprmemep.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2xevtrtcg.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gt2gabmoqnf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2sruixqkp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2nnvhuubv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2gleqnvky.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2potfzmzv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2unilqnpy.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2symmjgti.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2cajxuxgd.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gt2pibwfuag.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xllvzvjw.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2ugsvgxfo.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gt2zntutrxx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2gtxpcecv.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2uulfxtik.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2ebdgsgzj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fulbmzrv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2mnafzgmt.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2bqqxeoko.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdvgxrqx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gt2gwlrkjdz.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gt2wyiytuvx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gt2xdkxtujl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyuphdz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2jhgytjww.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2bwmtrxgv.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrzqcwvr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2wbgitcwy.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gt2vyhyqmay.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2sbhvuorr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gt2ghyziksi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2aiydemho.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2soxtzpyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gt2gcatjxkr.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2syvrwono.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2qbzkrjav.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2nzcijyla.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xclufqmb.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftdpphju.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2sjdzxkxv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2iqlbzecr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2ffhdyyez.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2ajpxlywo.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukhtyqwf.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2qbtnaide.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2falztdhy.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gt2nqbfngrh.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2tzvhzvpk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2kcwoowbn.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2dbdqtfoz.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2cbdytiak.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2diemeboj.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2cozwnpml.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2mmoezjlc.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2puywvmay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2yeshqnlb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2rhkiblse.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gt2pnlnccvg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2hcdrzmkb.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2nufhngco.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2zwzutfpn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2yzytsadp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2rsuxhwcs.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2hqffqwkv.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2qewenwha.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2hwzfuknt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2wxqsfewz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2zakszgwn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zeqvzuru.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpeopmow.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2hszqatgr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2wpvcdcdm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gt2zmdieezv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gt2qwzlkojd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wapgamcq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2moitpbrm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2lphavmmv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2ahqpcrei.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2nitrullm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gt2mqsauqzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2auwuzpfm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2kdlffgut.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2efanswft.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2vfsslwaj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gt2uzumpodg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gt2erbmczrj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2mbxnnacw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2pfsdvrmn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gt2lbshbfyj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2vfellwjc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ljcmpliv.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slwiitzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2dijgrejr.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2tlgrwond.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2blrdecaj.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2pxhkbhyw.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2prknynyw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gt2uklmevzp.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2xryvjqps.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2blhrtvbh.html


<!-- 参考信息 -->