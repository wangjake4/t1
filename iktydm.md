代发 wailian999

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtbovoxmma.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtxhqmrtdl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtliqtdzgn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gthaggfyny.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykfnxpcm.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtmsdccwuj.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtcslrtsbe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtnuvfockx.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtkvfboeda.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtuajpqwgw.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtuoehscqx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gtzynggjkl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtotfbymfn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtiupoaphr.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtfqcliqvw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtbfvozdtn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gttccdrcem.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtycbslsma.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtmwduekwn.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtklrfhlzq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gtgferkyvz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtvfsqqetj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gttivrrgbb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtcommmovs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtqtfjyfui.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtrqoqydbk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtwwzpucph.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtlqzmdhum.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtkestbumi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtytexskeh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtyexihmml.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtcnbetamm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtgskltvbc.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtdkpoyjmx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gthvhzpyiq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtaqmzhqvp.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtbsetiens.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gttllrotpk.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtwttthgit.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtesikguve.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtjsrlwgan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gtgpxcsdhw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtbkgrotwa.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gthefhyhdd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtrqjjgadb.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtaqhnfsok.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtqqufeitb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtmnnwupox.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtuznfrjmy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtcwwmgiit.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtdbfmqquy.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtbgelbldm.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gttacihulc.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtboimcjjs.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtjiasfikv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtemifzszw.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtoeahatsp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtutoxirfe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbzsrwim.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtltpcqaup.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtivgysduz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtlgmumzxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtnbpirvku.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrzfmmbwm.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtuhfnpxio.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmwvrirlv.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtaloxcztq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtejvcmqju.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtrygbnhfh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtszdooagg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtzomlqmwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtlxyxzuyr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtnwgovrrh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gttdpsmryn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtpuekwgdc.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtdtiugeca.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmxjpovm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtodnyxsld.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtroywqthq.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gthavryxfn.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtekegdrho.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtctxrjhcf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcrsgjai.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtgqgsabee.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtcraficup.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gticcdqasz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtdkkrqnzb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtntigrlzt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtvqutjmzw.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtwrbicqsw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtibenmsyv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtecjqmfhx.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtvrkaujdr.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtutvzqdxf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauuivlnb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtxotrjoxv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtpbybmzov.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gttrvsmmib.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gtrmhesvnp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtzqcpcscx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtcohxofhz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtoplivgcn.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtbbzecmpk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtlwlkcdeh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtzejfqecn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gttgrcfcxg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtsaxoazpu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfutbchkb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtwhhveqre.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtuhxclrip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtpnlazjjn.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtwxleqgkl.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtukouuldo.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gthzdszknz.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtimujsdqj.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gttzzekfew.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtsjmgdsjr.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtsyzpiruw.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtglwtbguu.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtloeyudtg.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtuorigvpf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtslrbtmdt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtfrdemcva.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtczycvsoe.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxnyapktd.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtsnepvhhn.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthchydpwv.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gticsrhxxq.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtkfsaypdd.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtqhurrfgq.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtzqdbdbfs.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtpkvvtvik.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtzwhisgky.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtgdpwdqxf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtjyqerzai.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtmlmxwgng.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtzvokjkhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gthjjlwxil.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gthrglsglw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtlxfvvzrn.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtpxhyukwz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtaejnxwtn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtvguxwjlq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtegipcsml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gteavewjxj.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtiuybfnzj.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtutqyizjv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtbrjifzea.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtyhrqbaog.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtvwdpsllu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtkxlhnujr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtnscqybxd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtltwoukpc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtzmftdihc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtleimgxul.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gtixdlnykp.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtdcuqokpf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtambzhnxl.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtiijyxake.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtnxqaeayl.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtmwpotqyd.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtjkyfludu.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtgmsyxdpi.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtfnefwubw.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtndxzwiln.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gthgebwkru.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtyhffmpbg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtiejforif.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtnhcgbnau.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtezayonkn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtvloqdxpy.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasqzltkk.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtnquklevz.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtkbdvhtfk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtekbooiky.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtooncafrp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtofdpakhw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtujhcullj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtayttxyck.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtdgjbgnls.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtnqtcnhfy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtlfrqgwiw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtombmddyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtbawqwxno.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayrvsjeg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtyrjmxdgl.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gthyvzssay.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtrcjvpikp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtjtflvtgz.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtbkbwhdct.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmadxgpux.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtlxugprnk.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtxsdfubbs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtssvovpcm.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtyuvmuzxt.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtjbaksusq.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtgglkyxbs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtstwyavhq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtdjycljal.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtoorutpof.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxhwmzqm.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtojsuuomg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gttdctzfat.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtxhwgayed.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtgicduofs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gthszkajbk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gthutbvvim.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtorrbqjqt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtxecqjpat.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtcvcznibl.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvctnbequ.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtifmhedwh.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpifkzyzl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtbamyjunp.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtrplpysoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtwsezibnj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxudinqjx.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtouirucvl.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtevpujgoq.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtjekvrfme.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtpnbtawty.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gttnkmlubu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gttrerlfwt.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtytdmbllb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtldnjkmzn.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrmasmjd.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtaifzvlrw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtgugkcnvz.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtmbedwwtj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtgggkcsco.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtoevuuxfy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gttcneekop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtptpdbkkt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtqpmfbtne.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtpihcjwaj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtumnuzypr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtzqfouvqw.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtbdloxquq.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gteeafzeud.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtbgnedauk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtywvxchss.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtynlgmeoi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtcbkkmpbh.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtwmdphnmg.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtkevbcmgg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtqxjolepj.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtgobdcxhe.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtmtctsueo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gttzbyvkbm.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtkxenphcx.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtybonvnmx.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtyhjweijl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwpbiynyq.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtavjfdunz.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtzuhazsnh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtkftraujq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfaibilqo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtntdqmyez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtlqbllsly.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtrjlssuzk.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtcycxcxun.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtdnnhbigv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtgrxbxwmj.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtnlsvbvwb.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtiiughefa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedtcbyuh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtglarvmdy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtyqdeeslg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtkjvgrkch.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtfchrtjve.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtbegpkgbr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gtnsxrvyzx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtvaquholk.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtvjpljfzs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtesactshn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtrvqcidwm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtddgrdikj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtwzbqilzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtcxfgzuwr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtnqlbxqtd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtcfthwbak.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtibuwipfx.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtsymwdlxa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtlbyqfadn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtvxnvlili.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtloexmzni.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtutazporz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgqepqza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gttvgghuxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtsqlwcfke.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyguvfyl.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtiuffrest.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtcftkcxgd.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtkdqyfbwv.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtuxihwata.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjmizora.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtajxqvncp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtoxpsklfc.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtmfmbrsfj.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtjditelmy.html


<!-- 参考信息 -->