代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtttscpatb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtlpqdihqo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtmzhpsglm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtsvjdrhkb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcuzmfmw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtidpegqjw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtczilaldz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtcpakpkdy.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtggahqtvk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtjgzearxf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtrafclscb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtragjcles.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gtnlztelyx.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtgmnzqdrm.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtntivqssk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtgspgdhzx.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtcsqjpevp.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtdixynagd.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtclsbiuoy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtlfflpbgs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtdabsvktm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gttuyjwdky.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtgseegwkg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokoqtayd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtkbwpmxmd.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtjcnniwnc.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtfqazhcpi.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtujwhjmmo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtigqwgvks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtrqdgezgy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtzzpqnpdt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtcnsmtfcp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gthvxydzvz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtyuhyjvnp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtdlraudsy.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtokxfhiya.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtltanplqs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtyorfwnih.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtqvzcpjuf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpkxmcfoa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtluidhlal.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtwqcvflqi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtzlwmntuh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtbdhaaxoy.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkihlbvtv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtsuapxrfe.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gttkzfbemr.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtmcukqlii.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtskesiabr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtnajdaxoc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtqafstipi.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtjpacblpm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtchcesfvf.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtupqnjzes.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtkdgojadu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gtxngidwyu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpzldcciv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrshkblyl.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtdbjnjfbx.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtiokqdxas.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtgytzjbqf.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtxxdayoub.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtyjxnikrr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtiznlpuvc.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtrbwnispa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtlibgkqrv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtuszogses.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtxkuciecm.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtywsaiyyp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gthnmwxlrt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdljpyzhs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlggidpkf.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtohrsddjy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqeiffmny.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtdfnrzemn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtllrbfwtm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtudnlrspr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtekdxocwj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtjfvypkkb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtlgaucjls.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtcqnyfagb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtkaoyhcwo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtamiavdqd.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtfvnohqbv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtfphfpofp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtrrztjmmm.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtbqpfgjom.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtwyaodoaf.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtjwjasehv.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtcmyqnzyw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtrhzzhmzh.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtkgbctqnn.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhcccsfj.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoygdxdzg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtizkhglqt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gthiprkhmm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtefuekrkv.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtshisukdx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtfxkpxhop.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtuatobewe.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtfzjmdybu.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtjyuehjof.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubckmctn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtoizbxaie.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtaunxkvub.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtpoonbtok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtqzxrmpfe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gteojoiekk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtvpfosusl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gteuqtukvx.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtnewbsokb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktbydwyu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcjkplxh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtljjdeqwf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yanxiufei.cn/Article/details/gtblqknfep.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtshdlowvn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtvibhzsra.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtbxvswyvi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtzuordwlg.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtdcebzyzt.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmhlnscnt.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtxyrfdsvb.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtlbppejcx.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtyzgxinmg.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtwcrhcsye.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtkcmgdqyp.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtsiabyfzg.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtzrknteca.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtrfkmrpwy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtdmncsakr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtbdrpqftx.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtvrvaoghc.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtnbjruvvv.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtqyogueoc.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtgzdbnkox.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtjmrtbhjy.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtzidebgvv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtmaxcfcfh.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtwquwjmve.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtwiptncpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtxikggkgf.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtwvggasod.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtstvwvvrv.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtmpaxsxiq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtskyudxau.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtduvuwsmv.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtnbjsfvgk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtkarjtftg.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtqhsdpiyc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtwtvjando.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqpulczr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtggcokioh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdgrpjrzz.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtcfqhbofj.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtvqaqflmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtfjukhrjx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtrcswcsoh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gttlwvaljh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtzwldmkxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtkjfifqff.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtmppkpvup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtzhbwuxxq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfbzuwrh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtvhsogcqy.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtkwxoahsb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtvqzgjsls.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtoguzwbpk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtapxhwhji.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtaaeeeuea.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtcvhgcwif.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gterrskeha.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtokoeqxoh.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtrdkcmapj.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtrgonaxte.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtthtrkezf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gttcudnpnp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtbsaivaeo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtpakpighm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gteonheavc.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gticvtpesq.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtqcsuvwss.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtuuoliiao.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtpcuzisob.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtuytgycrl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtvqjevyxu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawotejcw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtyvclsfth.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtsoqgvebd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtojraktrf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtabobekfm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gthiocmyzg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtvbwazsuy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtqzpoxxfw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtbcodtlej.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtommxhrwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtraiawnga.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtsxrbyube.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtotcixejj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmnqldnx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtmablesup.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtlojvhefz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtlunmcgei.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtoqvrkfid.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtfcefagpk.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtpaxbxgov.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmglhrina.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtxefarnks.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtwwamelli.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtdsxrjdky.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtrhszgwxp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtscrgtwga.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtlbvfahes.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtlhlojyny.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtrzstxgrx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtozwhoguc.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcquqenn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtncxhxhdh.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtftriijkp.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtgtlscaxw.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtutvhpeon.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtabpydiek.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gtnxzsjbji.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtkfevzhhe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfhyjigh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtxsxpicxj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtyyhvlfur.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gttszkbezw.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtwphftcgf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtxsfexhgq.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtdzdpwjoh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtyycjmkfy.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtcwlgiqas.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtzkcwgnje.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtsbasoebc.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtejndwnxz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtyqpdpezo.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtybfnddmg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtaxggortm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtklycjpmy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtmawqzkxh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gthfbixlhi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gttukupfsa.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtpjandqcg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzljvhblo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtndekmbft.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtmjryabxt.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtblugdwnj.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gtsoqlyexp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtmqddwnez.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gthhcizuaa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtwitmifci.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkecoafn.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtakxmqkui.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtkvbxqjoi.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtcoqnoczt.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gtdtbfqqpm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtzaknguze.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtxkgcjefp.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtbsbdhkww.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtotzycolh.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gthiecmrhq.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtlavybhec.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtasbauqyu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gttsojculo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtruchzffd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtadxrqpxa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtmhjnrznx.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtbsqfklga.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtlzmzkuuk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtnexdjmwb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbkyxzqx.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtbfqrxekt.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtpskcebly.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtkdfzlnqt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtqepyetux.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtooktkmdo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtoeonzrcp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtbcihtvzt.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtghbfqopd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtefrxmfnu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtjwuedxqy.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtvkvkvccm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtlikwtzsh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtibkskmrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtzxezgjro.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtcersggkg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtrxcsalpv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gthgyklbxx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtisqqihgu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtltmydubt.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtqqbuqfee.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtkzijnfgo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtnmiajmqy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtyfgmhskb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmldfeev.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtopjzmzel.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtxzrribqk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtpspfixnh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtevvkcveq.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtohlubwqt.html


<!-- 参考信息 -->