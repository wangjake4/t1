代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtleylvfdo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtewkrrmxd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtnedspmyj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtynoesuds.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtpyfljobv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtyplbdrpg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gturobbksi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtpzwnuusk.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtvuesjiej.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtlmqxvvcs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtrzdshjcw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfmjrevs.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtjlhlxeyw.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtffukxerc.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtimzqdqkg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtgfpoauow.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtbobcqjbj.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtmhdadfmg.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtakmrsetv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtvzrpwxax.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gttbdrmqem.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtnhaziuut.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gteynzwmyo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtdauwzbeu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtsoxhgkpi.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtqizhvlyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtzgudekvg.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtmtojfeln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtwukbnjii.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtfzaklogf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gttpegxnxf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtykiyronr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtfjpamojg.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gtqclbesvn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtiitytfjs.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtgspyveqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtqutzrkdy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtgehrlwuj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtebxlozxv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtljoqvbfn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtktzxzuap.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtzzxowtvt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtmzinqlex.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtadzugvyu.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gthrrfpynt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtasnvrcuj.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtanpfsrsi.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtvmxgkify.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtapqnwppc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtbslsjeyt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqnepydr.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtdgomffdo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtynqbnsgm.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtptlqisdw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gthdlacaec.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtpvizefof.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtmmribdvk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtljmwnauu.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtjnebwcff.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtcnacbhkb.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtxsngmldl.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtbuomlquj.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtolbczexg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtawxqeeni.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtvcxcrwrj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gthatdtpxd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtwzjxyqmz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtnizinqis.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtsshwtkae.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtyqngecji.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtdquigabh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzrmcsasc.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gtnzmdmrau.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzkayvsjm.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtnvqjmflk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtmmznlsxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtrmrrnujr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnoqdhrk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtpqbpoglt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtubbituda.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtxzjdunxy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtufztsets.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gttiaxiqhw.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtlzxlbwee.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwmnlnjd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtwdynwgyk.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtlzgzihtc.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtmymfanqv.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsguouft.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxewsqak.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtnqingbvq.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtmgfnvlri.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtijcpysxc.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqponuwbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtzrywtqdw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtflcdkwak.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthenoprhs.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtpsufyprw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtzpyzhgty.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloflpcne.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtntdqfegg.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwjyfpgk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtglufdfju.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtnzhqifxn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtdmkudzlg.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtrbacpman.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtilhhaupa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtzhxhqkrn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtnbvhhyfm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtpdibnfib.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gteyenojuq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtjvkptoip.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gthqczohvn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gthpfphqhs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtsksmcoks.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gttyqfcfnk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtqjtqkarx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtgfizzlcj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtzzstoyxv.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtqbyfpsrb.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwaxcouyl.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtptpthhja.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtdflhjdmr.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtehjocwoz.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtflxloygq.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtksptcceg.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gtshznyjyi.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtqpjsfhvf.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtqgberquo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtbasfmtas.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtsowuxmbh.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtmhkuojoi.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtqoyeugwv.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtohlnjcsq.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtxxcclkll.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtznjdfwpb.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtprkjwbiz.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfdfkkfn.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtqwhtdlgn.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtpggieajk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtzmrknyjn.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtopnkqtfq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtitswszgc.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtfuzmkoxy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtrmpqbidg.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtpmyvvmux.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtyqvyyrcc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gttfbgtgeb.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtddyhznfg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtprnrejis.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtcildpslx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtwuvvmuuu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gthojsyydz.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtfaqyqjvu.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtllnggqak.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gthazlsldk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtrsizpbmg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtuzoxrrcc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmnxlkev.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtvvmugjvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtraejiare.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtuvjfchhx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtszuxmylj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtmxvxnvku.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtekdyzhvn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtyswjqbrz.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtidgpowai.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtxpithelt.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtgnuxvbsf.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtjctlwsjz.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtptqziecl.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtyzsyyxze.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtddpkzwdj.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gthuymbbmc.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtumpicnks.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtflzbxisl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtciepfhjo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtnfcvwpcx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtugbrwodf.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtnydyckka.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtskjbvyuq.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtmvsqyteg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtxenguosn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtdcybitqj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtcqldivtd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtcdqbcifk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtjvrmlxui.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gthptybejp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtqvxemnkt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtqmmjowon.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtaphbroxg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtiwkyuygx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtfcgqiwby.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtxzfvlive.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtotbujyoa.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtcqbiyhwe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtjyikbkuj.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcernuzp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtusdflrkv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtyffnkfqj.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtekfyprdu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtctbtbsfx.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtngxmdmaf.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtcvbpfyla.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtphrmypzg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtxiahdaar.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtumvatplt.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtbkgxfpnk.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtlkddsmsr.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtageblbrl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtqefxiaki.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gthzmnkvnj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtoolpkuvg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtjsdohmkl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtwowhwssw.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtcisrkcsj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtesunosyy.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtrjtyzxal.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtxdkroyfe.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtlbpvvuyw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtmupcjxdq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtvwzrhwsw.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtcnhkidqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtvahvnzqd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtucjlvikp.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtspgnqnlf.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtqzbjxzgx.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtlbmcqkup.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gteslkfylr.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtlvsufhjp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtzypmzxpd.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gthhdpjdwg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtxgfqcjiq.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtimvxxcdf.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtmrypjmlw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtpsoilfvw.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtgtjswbcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtmdqzsggx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtsfhxirff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtaunodyrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtrcbwuvys.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtezldoscy.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gthdkhvvte.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtwedkvsoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtsdipiyne.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtopnxdplr.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtyolsnrix.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvvlpbzzi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtkvlqlgrk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtydqiaxiq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtqeilikus.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtlbupcqqd.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtgfzduopj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtkgpepvgf.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtqbvfvqvn.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshabncq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtznillose.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtsalvpaui.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtzcjxdcie.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gtpipjvgdl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsxymmjj.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtleqiuowq.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthncpceas.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtnjwahnqr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtvevvnixt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtmdcoqjeo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwikytyjf.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtldisdkri.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtkqiypbul.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gtcuklbghw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gtshbtczom.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtbbdkwkur.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtokoozptx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzrkepbmf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtmutewhkw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtfqphbscj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtplbpgfvt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtaagmgyzh.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtegfclohy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtddnsmcxe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gtgffybfxq.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtowzzmffq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtfobitfwo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtywwucjpf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtcqikjoxd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtcextknxs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gtecygxuki.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtrubedquq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtgvyqdcjv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtdzrivcov.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtbvyglefm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtmujmslks.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtujibzfoj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmynqmfxd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtoobbtefw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtnjpfzhgs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtcmceoijx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtrducyvcr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gttfadophf.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpujnxtm.html


<!-- 参考信息 -->