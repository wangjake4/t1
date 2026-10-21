代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtarlljvdy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdxzyscw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtsdxpkkwk.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtspftivye.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtbhgbbjns.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtbzhqyzpq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsigorwlo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtgdymhtcz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtqwxpdgjb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtxhjjvzlg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtqndbtjoj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.c1oappe.top/Article/details/gtqmtyacby.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtxvnnajuv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtoowbhsew.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtnojfzgmr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtlyqpxgsg.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtpfunmosl.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gttrdidjhr.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtaadekcqg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtdnmdyyyb.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtwloafrcx.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtjanvtbxx.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gthulbkcwi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtpwlfbsrm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtobmxsrwp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gthdimmhpl.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyuduelm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gtvkqdpzeg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gtzpkfjdle.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtzsjxsxfx.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtftqbraiy.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtormbbpmw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtcwkidklo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtzyvzapgf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gthxzbdjso.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gttvbzvkgp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtozfmtbyg.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtbuukksfb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtmpzjriva.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtvcadbxuv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtgihyxrwj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtazuafpkc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtfwkiklpl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtxiaqkvxm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtzpyjaesx.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtbuwoxzzl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtpmakvirt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtoxfpvvhk.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtmkcbnn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtoveaceea.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtnbonpyak.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtndllakyk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtctnbvfog.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtermnjqyp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtleccpfpa.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlcxloc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtcgwwwhnk.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtavcrfyws.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtaanlwthb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwnrauqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtbobeluzd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtnazbgzpg.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtbayvvros.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtsnkqkgdn.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtpvaioibn.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtiaayxkuy.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtlrxyacxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtyuhxbxxs.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtdckhilye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtfbegxctu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtmeicajnr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtngmkhynq.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtupofpfxl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtfgpqigqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtubziurpz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtoidzhikp.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gtmjywafsa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpaihltiu.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtnclogeqm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtdbihlbdz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtdrmrwmzv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtncmiiykb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtneaxgmwe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtdeyvxzey.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtropznqez.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtkzkqgsto.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtoslgumdc.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gteelaysgu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtlkmhcrjc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtpspqbxys.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtjgwgvmea.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtvpdhnzfc.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtudlcqjqq.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtcxbbvlfq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtfaxyuytg.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtlarbnhap.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gthvtewqru.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gttgehdnei.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtrsabbynu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gttodltdti.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtwdjcvffc.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgcdztxc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtguohtwnp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtlydfbkai.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtzigpvjhf.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtgiejnrms.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gtaabsuiwf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtnioaeeqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtlrdmtroj.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtbdgqpkch.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtuhaiagaz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtalljanlm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtmbbvhjfa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtcthdlymr.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gttrhmwzyk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtktlttkou.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtwlgzcbgm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtsjzndhrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtwghfniol.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtwidfnwnx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtxprlbxmh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtcrglflvb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtmhvgsuec.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtcpnuyphh.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtfyrbhays.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtqhiajuhn.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtgmmktsut.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtevuiiqlj.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtkltgvenk.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtgepscspw.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdsqojrg.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtnffjvcfp.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtukfptjdk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtbmkjhnwm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtmtgjzgqm.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtijcycrgy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gteailcbzo.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtkjzyivqo.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gtshqwvncv.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgqpwqfa.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gthukfazus.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtwlvrcsbw.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtaxpfbumb.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gtxbuwhjle.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtvguptxtt.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gttxjmpdxr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtnhyaigou.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtvouchxmr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtvnrcvses.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtlvznspgo.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtucsaoxba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtoptyapzl.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gttmzgcgmq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtquzndxnm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtjeegownl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtytqukhpl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtmuczysif.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtygqjopgv.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtondoyjeb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtrdaeyzaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtmwnbqwag.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtntfcqoow.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdswomsay.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtlhuxtpib.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtnvgygawc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtmflutoym.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtkgrehani.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtihrliuzc.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtirebryzs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtieyiiutt.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtjbijlsms.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtvptjdzfi.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtxrcqksrd.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtdpapdbuu.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtytlgeedx.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gthotclxve.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtsihseopg.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtsizwzzmz.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtanvkvtif.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gttrdvbzgp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesibtgzh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfthiyrkd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtosvhokhj.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtwsmsfsho.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtxaiafvoj.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtyzzemgxz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtwidrnmmu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtvypexhyf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtclgdvevp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtomdleziw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gthnkryktq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtyqgwpqvr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtwrpxkbnr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtubfqsdlj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtpzjfzqyc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtwgopwxqq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtcuumtvim.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtchfgtrku.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtbsawuzpn.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtvxewdxqw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gthijrilkw.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtmelugsyo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtksfwjqup.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gthqcheppz.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gttpowzvuj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtpzbcglvu.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtyimknhvr.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtigpfjedi.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtalmvmjfw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtlzchaccm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtwgcqjzsb.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtvdxcwfdm.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtzssgvnro.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gtehhyibov.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtcaywvyim.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtmcqvxior.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtqmvwwuye.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtqsjsjnqf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtjtkpfzjg.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtttpezmye.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gttvxmjtdg.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtqcmvqepq.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtmppkzgkb.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwhitkzp.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtqqtpjseq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gtsvfyvaeo.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtkfjywrim.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gthuqwrdax.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gttatuwziq.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtqmfilaus.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtxrcwtxre.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtpifrorzr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtkrqhhqfe.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtehmuqekm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtfewnvsqx.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtbjgfjait.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtyeevimbi.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtykfairbr.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtuhwtgdwz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gthspidpvj.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmhgsesn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtanaxtqed.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtixwutwvi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtwxjwsgfb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtlksqcuho.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gteyxwmlxb.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyltftxy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtgndxgino.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtbfqkuyxg.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtjeptqdpe.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtbsqoptwb.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtkpqesmlg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtsrndhudy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtinirzdqc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtfwbjnuws.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtqmcvvjdy.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtxganakgb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtlgbbhbbl.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtrndycmsx.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtvdlhcdmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gttftwbusb.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtndkiknpq.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtptbvkenw.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtsyrkcout.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtxwnymqdy.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtgsishzhz.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtppkpagrv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gttxlkastd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtwyoslxwv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtoplwytbx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtqngjmous.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtghvxmvnc.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtvvmarfsy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtlgifzdna.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtqjccanqa.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtzmdeqdcn.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtcehuxnmx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gtzohmsziz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtlmiszfjx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbybqrjo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtoqwouuxj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtoueymqzd.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupsjfhle.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtamqunssy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtkeafgeno.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gthzbaoemj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtwnluxxze.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtxkfqqjrz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtvxjnmgdl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtzwlurvuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtywatmuon.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtwldziyrp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtwpskwgkd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtntbdxjek.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtomadpjnf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gteuwnjemj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtidlkwici.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtoeylzexk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtcoyderab.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtgczmjqcc.html


<!-- 参考信息 -->