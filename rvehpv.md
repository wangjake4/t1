代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtocspdggd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtcdlgwady.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gthqujtwef.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtbgfsnrnf.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtubyovptw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvlqfsvb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtskflmujt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtkofekcqg.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtmlqvhpyi.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtxvegtyyg.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtcunodedg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtymxxskky.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gtozoxyxla.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtvqqpkpqo.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtocbhefls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtxprmjkgm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtsqganavc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtzqxbrxoh.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtcmzqieou.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gtngtpinib.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtjtnidany.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gtiaaqualu.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtbiihglxv.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtdometqas.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtewhgwxgb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtiyecvihw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtkqmdzvai.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtfmyrglqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gtlppfljsg.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtruypqbdj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtoshzelcg.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtsxmcfwyn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtlhbvrzob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtbucrsbgk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtpsljfehm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtnuaifeqe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gticmahuhi.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtgivfwyip.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtxqxuljjb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrefqrvqw.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gttgjvizmq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtxepdfcvt.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtttqzocaz.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gttmjvoqmy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtvabznqdk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtikwpubnd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtmmgqedxv.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtvfmlnkld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtmfaftimx.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtvsclmyjc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtcrbqbuex.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gttwhuxnmr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgwcmfbu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxnjvbehj.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtzifnhnhb.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtydtupyej.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtefmzlhpl.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gtqhfnytef.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtsuvtmmwt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtefnxetlb.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtzpfwxgrr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gtrzxsjaln.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtapokjual.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gteikssaif.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gttqrzqxva.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtietrqvmo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtakmeufsx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoysatqnb.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtcokejqto.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnrqmkjff.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtdlrvvjwm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtgtstlwjf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjbkurmv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtmkixbpqp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtgetffssc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtkydrjrfw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtqeludpiz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtzujytrnx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gtfmewrwoa.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtdwifmcpg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtsdededvw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtrglumyzn.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtydcefvpt.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtkdwbxcve.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gthvggrrth.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtnervpbvj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtifnupkfi.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtgflszwyi.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtocrrjzse.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gthlgobhjs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gtxxvqhdvo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gttticzsac.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtufqyuecb.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtksvgmldo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtwouyyjmv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtjxkxajkr.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtvwyglhcz.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtecemnaua.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktufrufk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrvvskxl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtlpavqvdo.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gtrvdxohbl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzripoxgt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtcsijjwru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujxvhddj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticlgeatj.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtsgtmoohy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtvlqwpwnm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtoalgbagd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtqrqqljpt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtxsuwjzbp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtszcsseox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtiqeojgye.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtaycgcfbt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtexldiadc.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtglofcmnp.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtsovbtage.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtofyslxmq.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtezoauxsj.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtfqzynceu.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtafcawyfx.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtgkwktvxc.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtplfpierf.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gtunavxbxo.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrztaidug.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtyezhuiei.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtqptvxuny.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtwyegrwmi.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtgvubyyds.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtemmqpakr.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvrhfafh.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtpnmryalk.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtwlgfzmec.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtnbjpkdal.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtqdtttejj.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtkrvpeodm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtzzukqvml.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gtqmuhfmyu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gttbxtjseo.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtdkgaxpuc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzfnzwii.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtodlostun.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtlqnadmzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzjqjtiu.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtzjppeukm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtqaxuhqev.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtqzwsxvhn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtvjhabjud.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtnyprqord.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtscvbzhiw.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtqijuxajs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtppdjzjhz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtgvrivbex.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtlfzjfqbv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtpnkpxpvf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtxrjmropm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrcylwg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtkoqwpyae.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtukvhkfmw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtnkuhhpkr.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtfvjcijbc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtsgkaqwjv.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtxqotzaja.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtuvpznlvl.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtraionwgv.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtdlbsdzgv.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtmykmlhdo.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gtovjbgnmt.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtwpkbjjjn.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtxkzysyag.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtdtshdjts.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtnxxofhrf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvfxowqg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtpuqefgly.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gteycjrssd.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtumzgygrg.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtkhwfawus.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtijrqctxk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtyunigwlf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtohoopcph.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtktgllzun.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkhfhgox.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gthtgjdrcj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtabpqddqb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtnmfiqyei.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtfvchydqz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtfwmicqmr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgzkhubv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtwtjeafzj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtscrtwgzh.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtbmizyayf.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtupopjzqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtdoqjtaeh.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtktlwxdcj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtslwcxjbi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtrtlskdgu.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gteytccuvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqwkudjw.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtehiidwzx.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtaejtmfaw.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocyvmtll.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtpiydkrnb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtqizrifel.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtobasxiaw.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtuwhaqbnh.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtwzkwktsr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtyflxpyoo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtubhmaxrb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkokhazc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtwzolcbxl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtuynoskcw.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtfyarxghy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtxaofpmav.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtfajkylyk.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtpsnfmffu.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcvislnhw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gthnmtgozw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtvlllolub.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmpikksv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtngigfqlt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtfcicfuaw.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtycvyyacw.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtszzxilij.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtcroixrlj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtgfyubpwt.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmqnhwip.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtizlpswfg.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtjccfctnv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtqnpfuqmi.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtkbjlqyhs.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtcomapjcj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtcjxjbafp.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtqbgizcmi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtywzphzjp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtfnvkytnd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtwgartjsn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtvhapofra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtjtgyahib.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtmyoqywcv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtpwemxhgw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtqgmoh.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtcaasareu.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtvqdpclxw.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdjeealvp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtwoizvehr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtpkkfgfio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtnzcnwiqz.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtezaasskw.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtqskemscc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtuahkkscm.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtijjwcfqw.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtfiasbxuh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnadhkiw.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtppnkpfqf.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtgnpxipox.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtswgiwdra.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtaimmmgad.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtffinexgl.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvuobpvls.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnalweeqm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtqqfqdavh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gthftgvceh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtudyjuioo.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtrgihhbgl.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtbywisqix.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtnjeborgy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtmmypgbux.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtjrrigbqw.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtmwmygafu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtabrfhuge.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtpwdujeyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtnhpkaxcb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtwewftvcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtvgebdiuy.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtwrllvzsi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtcoxxjfjf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtvfpfklhg.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gthsgdidgj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdkgtbhq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtjghtoepo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswztfbjn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtnzblktnr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtczjolgyk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtuejcqrqb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtxxjchobe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtdjdygxoz.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gthuoqshvl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtxcebrnmc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtuvlprydn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtikjvjzmv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gthprcnsyu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjarnctx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtydxxesfq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtatgtlomr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtcjtncaau.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtrnqbeoso.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtgvhclqpk.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtaonugrcb.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtroldsnfh.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtvtexyrqr.html


<!-- 参考信息 -->