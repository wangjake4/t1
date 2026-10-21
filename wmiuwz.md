代发 wailian999

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtkbalkrjx.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtzgopbabl.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtpfefyzyt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtznbhxlsv.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtypatlnah.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtdzzmigtf.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtbtssmxvy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtoomabltv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtyzsnyeag.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtifcmsorg.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gteideokbl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtoykhwjkc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtmbdbbwrb.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtahjlrfrn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gthpdkgpxg.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtkvyqvrfg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtqukzhbfj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtnbwfkzin.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtlohpvqht.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gtbpnupwik.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gtirmlinfc.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtnwhbpssp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtwljrvbjy.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtoenbwvmp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtovhohqrc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlzxyunfs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gtxbxljngl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gthuoteuee.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtcrclopyu.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtomkpqzij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtedbulseb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtwpymprfc.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjmsmxzu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gtvrpmeaev.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtgamnkezz.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtgxwmibyu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtxnifvatv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gtmcjlhsnq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtxezfcfuu.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtyvqupots.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtomvlxgpb.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtqrsoacea.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtzilubvui.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gtanhshbgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtqajfysum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtnvebrdls.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtcwyhdcwk.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtrpqtnikx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtbehycbfy.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtvharxbnd.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtcfvhysog.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtvcvpwdqy.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtmblvbkkr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtgoiqghfy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtvsrjssnu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtekrwcnsd.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtjiuvdoqi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtgbhpgsut.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtuvloevtc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnrrzrvew.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtqxtgedsm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvygzgzky.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtspxfbxex.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtqiwrgfkv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtqixjstsk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtjggaakwl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtksqmpgrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtahirbxea.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtslahprtl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtuhbnogdh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtbesmvfwh.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gttoeqlnho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtbliohjuo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gthtowamio.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtbfcfotlc.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtrnttkhuh.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtvpcyiyhd.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtecgacomw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtaoswgsty.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtiywyhwkp.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtnekoqrve.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtxulewgpe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtcwfhxzyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtpbzddgrf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxaudgrbh.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtnirrbzit.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gteozcmysk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtskttkjyx.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtwwlhfvjg.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtznpkczsn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gtewwvmkbo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtevudtloq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtnejycmjn.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtvtfxsvvg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtcqxvlgmw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtnupvhfgp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtmuwhkmkw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtzrohnahq.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtvxmcfvjm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgrhpzjy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaflwsim.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtsqdgbdts.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtbrmzduqr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsnnjnxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfdmfads.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtursubdsu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtgkdmbzal.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdmylenc.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtiqnmbeuy.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtsssexzzf.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtvuxcvejh.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtskfuumzo.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtwubwnvhr.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwiqazhcp.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtudhioags.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtwwhnpikd.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtbctsrele.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtnbdekhcp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtdpzhdqno.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gttndiplfn.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtosikrbyq.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtmnxxigle.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtwabblult.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gttheipeas.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtkfoeryyy.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtflvsdytx.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtdjrqsvrw.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtcorqtyrf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtmityozvm.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtryrfviwx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtxgdrfzjg.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtbtylcmbn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtyvwxgvmb.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteknhmgik.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtpcqbaosg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtxyuisitj.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtlzylnxaq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtwoclovyd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtnnhycpir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gthfpcogch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtcfbzntlk.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyfltnsa.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtsztfzecj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtgienqyar.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gthafnmxix.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtvqepwwzw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtlbmqilrp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtzzcxyjiu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtopcjgfei.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtujevbarr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtgekktlgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtwmgtltgp.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtxepnuxdj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtvtlugeqc.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtxthpldyf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtdkdnlgwc.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtgkfjlzit.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtdvtzmkkq.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtloixwgtp.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtxmolbacd.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtlluulvrv.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwykrqhht.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtwhogutfr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gttrwdsgtm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtghumtgqk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtidzqkwaw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtnwcatdcp.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtbidnstaz.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtpwnldetw.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtlypvvjwa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxpemsnk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtyjhsnvuh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtusxxypqa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtimcxlgno.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gthwxjonjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtsriuqvxi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gttvwivsoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtcayhuyln.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtvsdbwfyj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtrfppbmmg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtygyuuvug.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtjojkpvci.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gttdonoeqe.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttndyzewo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtprsznblz.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtanobeads.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtyknaqxxb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtkhbhregk.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtbljwhyxn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtkjscszqz.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gttxrdvqnt.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtlqvxarqg.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtmlcajovh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtmiyoinwd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtgxvfezmc.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gthfflrgvj.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtvnpzmffo.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtcfihwtqw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtcnwyruxc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtbitmniiw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtwxkikdjj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtjrqinfap.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtjjftlzfw.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtgqkongoi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtuqrqmoor.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtaqrpjrrb.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtzrdkyvmc.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gthqahozln.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtcguvwxci.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtavakcfzp.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtgprrjobh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtpxmhbzep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gtogbmazio.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtlrqlvsbf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtejwcwfre.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtchrndlze.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtitebpwdd.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtkehlajvk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtfmnjnohk.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtxtgsdhxk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtzkoeuqad.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtxtfheehi.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gttozuyktt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtjfdqfpmn.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtxixctute.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtndnptdzn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gthpblqrjj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gttepxwswq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtkvnsbkqu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtlnxkrkhr.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtdcwigthu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtppnacfmn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtmdgtiohz.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtkksqxzux.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtmjcmsdjc.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtuefvuyzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtrygvfpjd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtlpubqwuk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtfeiiywek.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtfvqzlpxx.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtandrzpdu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtqysarxyl.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtgweztfop.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtwkacstjl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgkolwtx.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtxcfcycpc.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtaxwlsjvt.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtnhlbbggp.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtzicwjzbj.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtzewxmuqb.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnqxxqlga.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtalwncpac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtcztjziom.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtfklzpxmm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtayncezqw.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnxdezum.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gthinjtjed.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtavsctcxi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtmjzkhkmb.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtmxzuouxt.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gtayesoasl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtzmlircii.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtvpysbstz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtomcqtvvm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtlrztmwpb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtnlupctie.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtyqgxdmlb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtrodxnmed.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewwqeonn.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtesmnqihz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtsbrwqpvh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtelhrfelx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtdqyjxlye.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtqbjrfirq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtvqxfajly.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtrtfiupwt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gttdpijggz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gtofijugyl.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtetgljevs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtnxkxtskp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtusgicszt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtejeyhruc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtknbaqtjl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtwauxoayn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtdfexyeyz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdsembikg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtrnldubgl.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtimrktyov.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkeraeawe.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtkpvzviem.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtjdawvxpx.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtwygqkkpa.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtizxfcsae.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtjrhhmihb.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtfipiubzq.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtrdvzsnlw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtobjddloq.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtvkmxwlzu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmvdixcli.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtpleqnygi.html


<!-- 参考信息 -->