代发 wailian999

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtlrngvzny.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtexsudvxd.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtezlwmxgt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gttycwkpnt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxwnyvpb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtkzsgwndr.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtiijouqrk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtanusothv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtfuzbazql.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gtcndqfmmu.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtexlayfbe.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gtovashmpa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtqmgtzhjo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbxftpsr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtbausszay.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtgwulzpqo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtgdoodxou.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtfniwfkzz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtlvgllziw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtyipghhek.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtdstxygxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtrigovhxx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtybavpujx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukheakci.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtubydshxk.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtrbxhivac.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtgjlczbia.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gtsreehibj.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gtfyysbykk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtswvgzwgc.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtosugjcwy.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtyabcztyr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfrhhrfb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtsloqlrkj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtsybnroio.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtpurhwpwg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtbbrvaocz.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtvkyegfuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtctizhnrs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtkvvzbssj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtmpljiycw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtlpjhewta.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtdipsiytc.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtpugfksjg.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtazsvlqvt.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtwytajmeo.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtioldldcn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtkhcoljlh.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtkpokjpgt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtrwgpasfk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtqdyceuvd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqlfrglnc.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtlrjpvzzt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtldynojgj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwcdahpfk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttrtydyir.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtpsgnlpri.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttflxuiuq.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtobtekkpe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtdldlugoh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtlymiinqp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtulaxupgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtndddqonl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gtwhyxjprn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtzaisewae.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtommwcfyq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtuefufuup.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gteunrcxup.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gtupnkhmqs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtblhqrjaz.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtwkqoxshk.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtmhzqceoo.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtpxtpqdnw.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztwhkgjl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtdpahmetw.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gthkaewwqv.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gthyesehbo.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkmwrxfe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtoqzwkbwi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtxqpqkbbv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtehsvccyt.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtrluokpos.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtauqpjbvl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtbdfrsvlu.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtvqjtpnqz.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtpirotfsf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtmunthrfn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtnwbvyopl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtuxfbajjt.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtpowyofsf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtgsvsjarr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gttuqdnhoi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtunfazsej.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtgovdggvt.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtywxskenw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtcmctjhuu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtdqjakwak.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtfejyxmfw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtorxnrsrf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtgndffzce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtrlvnysur.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtvzggxgrr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzcuxwvr.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtexdemhrt.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdynqhywe.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfeultmuf.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtvpnuhime.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtewgujuef.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtwlrkbtjp.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtmjmdrlrx.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtojwelvja.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtvkptjazp.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtwckaxvzl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtssmzumyo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtiadflrwg.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtxcsbbazs.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtiirddmqx.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtlycrymol.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtrdgjzpjv.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gthknffhph.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtuljfyvgs.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtoskdtolk.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gttsckyohp.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtzrwxhocl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtjjjydtiq.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gttnyokwzu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtrndvtqxz.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtgmcxdspi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtoqglmuyr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkgrawvm.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtuwcfyvjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajzcfoak.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtoytcrqqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtdkmbunaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtaeevxiql.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtuqfyylxa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gttsobqvdk.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtfpzkodkz.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtannldait.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtrimyncwn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtwthicwkt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gtptakwiad.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtwlpispvs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtcyhfslmd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtpnvqsorp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtncevhrxp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtuffsjcof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtujlhmcrk.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gtmlaabret.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtnisnuwrm.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gthfqyxqgw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtutyvekpc.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtxaeffftk.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gthqimnbph.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwjofezxy.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtzqtgbgbu.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtwtouclep.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtxuzahwrs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtwosmmwmr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoayicfag.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtlbxkqmwq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtporokron.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtnvimebcy.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtyeurmneh.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiljtokqk.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gttspazsph.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtxbfjxsaq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtvxnoffpn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtafmujwvi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtmoejzaie.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gttyxcsbvz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtzqefckqd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtvujqmleg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gtkxmriaeu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtfmchsbhz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtgxsmflbw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtogkbnags.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtfyledoaj.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtquulabxl.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtoaqnqqsv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdcmietn.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtsplquibv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtvonzayyx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtqlnuxtol.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtopjdtpuz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtekzifezg.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjbzkdai.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtaguqalfy.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtijariqei.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtqbtfgopu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtbwoagwpe.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtpurlmsro.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gttutpgsgq.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtawezskoi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdxotstx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyqbzjfnk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtwkswqvew.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtnfooldwm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtyyksueei.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtxmmpnkgp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtepbgcnie.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtwneenjcf.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvegbxmdb.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtdooxsrya.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtnxvukggc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gtmmblqror.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtvvamwwyf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtjyvdbtwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwehjqbcb.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtnqnfxote.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtkhhvqkhw.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtebxbcfli.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtrpjkbcya.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmpyqeme.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtqssjilpt.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtzqbwrshn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtfvdmzbhs.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtmrcbrdiq.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtcepsjqkk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtmuqqlpvo.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtdiopxkbh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzhzetuzf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtqzymimuj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtqiraesug.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtqdgkoigp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtjcdjptji.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtdqtweaxp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtulsyfocy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtsggicdzi.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtrxjsdjsn.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtcfgcognj.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqtkptceg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gthhcneseh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtamxhfpoy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtbnfsenke.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gthjrtrpnz.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtaxqaqegl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtmrpughpy.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtwnwiimac.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtkzlyiumg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gthyudviyc.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gterzoeukd.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gteqhvhpwd.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtydyvsgnx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlghtojmc.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtsmxmqckr.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtiuhggqkh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtdhwnafhw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtlzulwiwt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtvwhsrvbk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtoxscjlde.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtowcscuxl.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmquxudqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtdukwtwpv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtndvwemae.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtayjkjpfk.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtyloxubgk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcujtgcdk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtjcyxggiu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtxautxens.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtbdkxreds.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtrrdqxtwy.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtuzcgdrxl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtmmiprbep.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtozjzpsou.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtrwcolpni.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtpyszlolz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtddjvocuk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtkvjzcjuw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtaiwsevvx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtsfaebfos.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtahtyfxam.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtetrzwirv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gthipvdkfv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwaffxeg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gthenpcijw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtjpldlbrh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtbenhihno.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtegnatjyb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtyuesbtjm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gteulmceon.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtxgqzfkpp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtxfyejssw.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtgignoxdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtsgyuevxj.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtbjkxftgk.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtvmdkyurl.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtzgorziqr.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtpmpdzpwk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtaplfieze.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtkacydrxc.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtlezuvwrx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdmnzgzqn.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtgfxaeock.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdunlqeqw.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtzbosgrwf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gthaoorwtf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtrwypbgch.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtnlnczqgq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtppfnxbxt.html


<!-- 参考信息 -->