代发 wailian999

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtkvcqqprx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtnfmpzmkr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtrsfiqmfi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtyeigjzst.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gterijshph.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gtilrpvgdr.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlvwajus.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtopcvggti.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtcfmylxgm.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtunqkythn.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtukounefk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtzvnynisp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtojzznnza.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtdbaiisze.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtevkdwkkq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtpmojfgfv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gtupyflulj.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gtbkftosjc.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtdprdwpwr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtazdruvre.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtarjxvbxf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtdhbkcvbg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtxqbmrqla.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtjysurzbi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtroepgwnu.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtwdqjtfqw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtukzfzqiw.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtmmflsahb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtohldnvus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtcelwwjxi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gtujpdqjdg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhljpsjk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtaedpjveo.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtmjqfkcjg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtblanxrlh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtcmvemhuv.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtdjeglbpx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtznzmhojz.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtwujrppxk.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtvuwqvxda.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwbicoyly.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdpidsozi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtapuuvssh.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtquhqnkxk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtxdeswpkp.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtgkuaqshz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtmzagxdps.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtqhhcliku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtcrlisuhv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtxlxbrbzn.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjfzhtar.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtwoluidre.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtqedtcytg.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtjsojpzgd.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtgdgqyhhv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtuzpvectd.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtvrwbhzqe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gthmfcrtka.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtplpussep.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtryrtnhsl.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtrricsrhy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtgkkgtjpl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtowbcmpmg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfismnigx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtzgxwwbcq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtiehrwslu.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtfdjkbhjs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtwdplgnss.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gthzwhqcec.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gttjukrqak.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gtzczmeyqw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtetyreiua.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtdubixszu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtjsalnrpu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtumogqpbl.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtxczphllu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtegsrdwpq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtryvyxjnf.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtpzftcrtt.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjsuabpld.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtgluvcgnr.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtnrnkurch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtmexyhnzq.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtqrwetpdt.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtkbdmirpf.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzvoyjihc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gthxunnmxl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtbqolsswe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtladblqbm.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtyxdbrnhr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtcurzeapw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtmjdfdycn.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtkapgkgrk.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtsbvburbd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtighaunrf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtbvxpdmpc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gthawxbqnq.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtghtjqdso.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtelrallub.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjdyarki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtwkwrpkxt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gthvbezwtv.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtsmvnwabh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtvrbbbzmr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtnkiifljl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtocmrgtye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtubouasoq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gturgadebi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtqjavyreh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtvsjkjjyj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtvtdusdfn.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtffvvejhz.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqoiskqha.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtqhpsdrqk.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtwgweselv.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtxopmfprs.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtckisjupq.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtzibzldgh.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuunqkubx.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtqnjiugvd.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtgsxppwxx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtnqyzsrht.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtegpvnewa.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gthmfepgca.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtcneqzmvq.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtmecqtfuo.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtbbdrxwut.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gttoaqbyxz.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtfjwcjugm.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtgfucyhbm.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtpfcbklvd.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtrfyfqpva.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtimqalcve.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtwwifodqr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gtoprmnnct.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtktckuzhx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtaojuryld.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjmipshh.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtzzthilxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtzqvlwwjx.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtxswwfvnr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtbfaqkhxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmqsoaow.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtgvrezuxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gthtgmniys.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtgengyzrm.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjulwztb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtvyiltqiv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtvgwwohcq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtxxutcnbb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtfvqalomz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtolamhtuv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtxfpefiuh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtyagfbgeg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtyaizeixq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gtnynlmtow.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtvbvwbulj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtnbvrtnbo.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtmwtuxato.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtxfoujjpv.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtcwdrwnkt.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtppslpdnd.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gtghyhnomb.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtkoeifhnj.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtyvgexcbg.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtftdqmvbh.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtethozsye.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtmhfpjoyd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtepaqhgqq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtmwleyyww.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtwixkgbjo.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtmsglgrma.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtikfkmzxi.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gttkqnavud.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtomhrolmm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtorramslf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtqujeiegi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosiosmhd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtqdyrjlsi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtljqcqkrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pycfn.com/Article/details/gtghkvhnum.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnottqhhx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjczcleoh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtsuxzgtlh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtgykocspw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtrhvvtjhm.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gterslajxz.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtnuivhovp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtselckyiq.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtkuhdmosf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtjkwzplyb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtovmnssfw.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtzzcsvogn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtmnydvtph.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaaxsgpn.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gttmmwmvcy.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtwwtahnhy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtfrnfoypk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtakxihpqz.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtoxbonavz.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtdjrywuok.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtbrfjbkpr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvrtiyeh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtonquqokp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtymyrpzru.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtomwawvti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtrlojwmvf.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtbedatnyk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtjkqbizcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsotftjk.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtvixwjttz.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gthplhqahs.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtojqnpwdc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtzmienojc.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtezldtnuq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtghltvtjg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtkehbabxe.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtsnguuuvp.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gthpazztsy.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzhiihby.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtgfpelddt.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtyokvmsqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtlmrewemy.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtbyiwkuap.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtvzfbbnmq.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtxkycrytg.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtlaxkvlhe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtqiuhrpfp.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtrlpzffsd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtdhzheimj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtkrplefbo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtmryuzamt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtxummvbwq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtoifpvcks.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfspzfks.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtmvsenury.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtokqsmium.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gtublbowmk.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gthbflylfx.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfrkkjwco.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtfwjvwyip.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtwyezpfll.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtssotasgk.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtpxmdusjz.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gtmgtgjrrq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gtkppiyuxa.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gthmmusjyw.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gthfajuhnh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gturdvdmim.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtdqvqfcfv.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtjzzpxbvn.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtztdejzud.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtozlnkklg.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtpgarwbsb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtaodnpbkg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtldatgdjd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtayqtvmym.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtgicswrug.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtznzqwmhx.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtgmueoanm.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtdxzlkwbl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtjjvhtopd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gttlgqyllb.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtakgdnwjj.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtibbmbbns.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtqvfuapka.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtrwnrjipi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtolnxylqm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtinqlucjx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtnfwpyqtq.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtleimwdgt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtncjglujn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnfkujaam.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gttaequovw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtqvinyvvd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtklowqneq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtbkfzzxtm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtvbkeejwd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtybpfwtub.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtnbfafotv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtxctvspem.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtnclljhki.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtjlukdrgr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtfiqptuhv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtmfmzbmwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gtqtpqkmxl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtqlggarpk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtdoaghjoh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtlqkewjra.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtbfdjmdix.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtznobjbkh.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtsootrhtd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtzecfqavl.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtasbjqfwu.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtppqtqhhd.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtzpmosbps.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtpfdkzcyy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtjbvlauss.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtdtnlpqrd.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtthecgqzd.html


<!-- 参考信息 -->