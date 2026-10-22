代发 wailian999

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2noegnbim.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxhqfppf.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2wxlrdssq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rutybfqa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2xwlapoic.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyxsjwyn.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gt2vlduwvke.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojlcluym.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gt2mvgdzvzk.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gt2jhnjwjpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gt2muiksvbx.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2wsfyksvz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gt2opbcuxpe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2eqodtpyt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2eeblipaw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2xpwwseah.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2dggvusln.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gt2codqhfzr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2heifijcs.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gt2hpqjbzyg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2dopqiktu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2rakvkroi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gt2mtpumjow.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmzwtysh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2utemsmig.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moryfflg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gt2ytkflkri.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2hkpkgxcw.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2mgprolix.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gt2mgjukatk.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2ljchhgak.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2tcidfwbl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrxjpiai.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gt2bkosjlra.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gt2exojqnct.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2wfxkmggg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gt2qlgwlojs.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2yrbqgkry.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gt2xgeoaebb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2lvzcghlu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2bvmmjpcg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2jzbnrewo.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2dxzoimub.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2myjxbgcd.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2gfnkigqj.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2lhiindfp.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2hnsbeagv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wznkciii.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gt2zdawyrut.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gt2vnmfynug.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxkgwvab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2xouvqwem.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gt2phncmvvn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2rszgatqf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2ijsxqfek.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jsoezltx.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2nuwnoukh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fhrbkprc.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2agdpgthn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emddfggy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2oqasanhs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2bbblhnhs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gt2quuwflap.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gt2xbmefhxg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2vpejbxxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gt2pkfqyfcz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gt2dygfbmso.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2vnfvxkuu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2bunxrkqp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2yowmjndo.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2tldzcpsy.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2fyqjovwe.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2upyxuysx.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2wirljaax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gt2mgoibair.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2unlrjjhx.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gt2ncftfogj.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnkduuxz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opieefge.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2pgakknyk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2qcwjbate.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2ynfjatqd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktmskwty.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmwpqphe.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2kqlxvfkc.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2urwcogts.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2cxlhjnzg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gt2xhontbck.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gt2szrhfmbu.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2oruxdnbt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2ffisstaa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gt2hczklhpx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2sclwbprl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gt2kmaovfpe.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gt2brtrhtwk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2tftzztgj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2wkiqojxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2kuaurcqu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gt2yfinkcyj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hftljihr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2fluriuib.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2thcginyq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2qujtcgjc.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqcnuaun.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2qpemeknx.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2dsyxuukh.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihnrwflx.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2gdonsmpx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lysioiyw.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2zftqkxua.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2ruzckbet.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2eajoygzh.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2zvbgajob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejqnrvif.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2eagzsyan.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2rsygujxy.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlvxyjpd.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2hyiuoxcn.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2dqpphvfh.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2nbatznku.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqcajaor.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2rbtscblu.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gt2hxvmcpxz.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2gvowjsjh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gt2qekxcsma.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gt2pnxxfkgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2arcnmkxu.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gt2avvakmad.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2nirzkkuo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdjeiphi.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gt2pgqowckb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gt2ciqcfrbo.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2bxzgufsn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2rzbvwvvd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2hzzjlcno.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gt2vvbhwbzq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2tryhbjtm.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2myzahblb.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gt2usltvgqc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gt2pehuhecy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gt2ilazmdoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2tzrjlcmc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wliqmnjr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2vfvjizvi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2penjngcs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsqusdok.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2echdmvtf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2bashqsbi.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2wjzftzbi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gt2chuyfotv.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2agvylglw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gt2suevdemp.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gt2twtxdhco.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gt2rkhpiluy.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2rjoomdhr.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2mcmcewdg.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyffdfuc.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gt2qrdbyqle.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gt2gxvxmknh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2mjwbvvpe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ffoblpfa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2vgnjxtiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2ejqduqxy.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2cpllmqhc.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2xvvtuphr.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gt2fsvhzkme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxxdanyz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gt2wyvhcxog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gt2xpxjtpcn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ghnptljk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2ycvxgcra.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbseju.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2opexsjuc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gt2akibkgkl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duqmipla.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2iqpdnckt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gt2nzcphtfr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2vzwkukap.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2amavcyxq.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfpfwlep.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gt2rqklrkkt.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2jxrhftmv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2xvtjwnop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2hodvntph.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gt2fejigjkn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2fcvuhsbr.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ttvsrlrq.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2mybfmbmt.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2rovmxwww.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2qxmfpgaw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2tpmipvcr.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gt2lfpgojxs.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2jsakhqep.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2cquhyxvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2rshnhned.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2vmvxcxyq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2gyqhjmho.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2uafkhgrw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gt2cuwpkmbd.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gt2amkfqwsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2mlpmrcmu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfhwycuo.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2noojybpl.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2lviepbim.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2zkasbwoz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gt2eqelnvcn.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzbexfmx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gt2rvnlooeu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pylfmecc.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gt2jaeeuiuj.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gt2vrqbkvwv.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gt2scejnogh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2zcadbglt.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2hrczupgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2krvoceuy.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2sjskwapy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gt2ymdsptor.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nobyktqj.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gt2iyezvsxn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2jfpektif.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gt2hdydcoyh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2yzulltvk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2odnbkdyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqhylfgh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gt2mgvsezru.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gt2mmbswymb.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsqctspn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gt2eyjsluxv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2oqspatpk.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2ntbdkula.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygfdvplt.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2pzbsgqme.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2laigmdwj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdqtcuwi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2yklatlxi.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gt2kwzquxzz.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2tzmeacdo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2mfeocnmt.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gt2pxvwhkqp.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gt2xmgjtqpw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgycslbn.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2htbxmtnl.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iynigiuf.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ucbheojz.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2khuorwao.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gt2biyfqurs.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2xjttdvso.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llmpvxwo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2riogvhdd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gt2efufmjtp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2xffjubae.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gt2mritjphd.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wajscveb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gt2lpsecdtu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2eprzzsps.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2aiqahfof.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2eiwhbzbg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poilhlue.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2elumgcac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjsyyqbh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2scpsnmil.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2vfdlornp.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2lgoonyhe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gt2qxsceyzb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2ymhyptfa.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gt2wnhnldia.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxrxqjil.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2ojtdeimv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2kgwyxwvo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2pqinnjks.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2eihgmube.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxenxtyo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2xzwkugmh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2aowkdvip.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2hdzrxqkb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bswuerav.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2tgcnehvh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gt2eimgovac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2asjcjywc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gt2sphusqed.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gt2turjboqt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jbavtxrt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gt2btrfqcpz.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2fidzlsup.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2ncqwpfzb.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ihwytoto.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2gdoipltg.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2hycclles.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2ououabpe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gt2rtvdjhhw.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2cwozwzao.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2vimidrfy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fnqjktqv.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gt2uliwmwvv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wiyisdak.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2jorwrvxq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gt2vuuoshym.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2gbuugkup.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2anjmvsqc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2efxbbcgt.html


<!-- 参考信息 -->