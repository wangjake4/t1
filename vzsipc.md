代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrhkyvoui.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtbjcwhnbq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtdsqyuigx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtkkerwkev.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzkeodut.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgvacxna.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtwvuplgsm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtnjxfyjcn.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtajnbxvhp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtpokdbxyr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtswgomjgf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtdfmisaps.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtrohrssfe.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtjtwxykeu.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gtianfxhiv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtscwrrzoz.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtzbhosvtx.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtjfrbrzhh.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtykqygldh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtrsropnuw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtsaenkofm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtvqquejen.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtckqspsms.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtzkyzlacb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gttqflyoxq.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtfvrnhjcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gthdjeksmq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwerqhck.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtzydgvcon.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtbxclyzwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtdujgemzp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gtxksfexjg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtljatnpfn.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtbapsdeth.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtwuacrqoq.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtlldzfjqj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtxjlpweay.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtxncrtiot.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtfxatudrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtfqyjbdok.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtuvnixlco.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gttnqdchxs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexbabixb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtiptqivns.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtqlqxvagi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddbmnqpp.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtzhlwttrm.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtyusbpbka.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtljccvcva.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gthlunlfxg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtineajyvn.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtaavaueul.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gthuogiqvl.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtzdzwulor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gthavozrfw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtsabscamk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtsqumxouv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtelhdpmdc.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtritnqmgb.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtltmdogab.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtnegiinlt.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtfgiqodou.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtrqviuvbx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtcelzbuhn.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtmhdqojza.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtmpmojdry.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtazmagmfr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtflhuxukb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtddnicyym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtufunytsl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gthbscxxwt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbgobeeox.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtxbwblmsk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpmcbfeuj.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtxcvrmjid.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtmqvmboiu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtqkxurouo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtupzajatm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtdtpfpqny.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtnipgyewv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtmykavhji.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtkareczdw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gteneqedgf.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlkkmjrh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtrubnwyxm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtlldkubqd.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtvdbddqyv.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtxcancdkx.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gthuwdwdng.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtzaykdjnp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtayatlatt.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtasizxxlx.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtxfnvfcui.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtzgpbapab.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtvaphpksc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtyckogewt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtpgkbcwvl.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtokyoylgk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtpabfoqar.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gtijzpexvw.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtygrqyqae.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gtbvgpqemk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtwmuuaejm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtmgxguuzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtcuawaalp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtapapoylp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtshqtmiia.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtffenugzr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeaxdyph.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gttgdszcly.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtyceyngpr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtofmelxki.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtcekoardm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtaagyxlri.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtrupncvka.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtpghwlxbh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtpplgheso.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxeesjka.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtkvoxntso.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtjgoqziku.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gttrfvzmos.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtexqerrnp.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtkvstggtt.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtbujgqiol.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gtcpqggcxv.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtblhjaqkg.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtniwqlxjz.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtzraovuig.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtbbtoxhsc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gtyzvntcej.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtdpjouabb.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtuvcnohzj.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gteqftpplv.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtpywcwbyw.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtlkweyrut.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtodsrlxhl.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtyvgmehxz.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtenthrjdq.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtjqfrljxk.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtrshymvoc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtvevrkvea.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtntadieyq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrezlfdxj.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtjooebynj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtpzzwxppk.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtybtnolid.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtbkgdpoig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtjegfdped.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtidbmzbqx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gteqakvscq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtansxqplb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtjwzdrdhw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtzyjrrkce.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtgyebmgrn.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtzwlhenwl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtjfdgokkm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtziezdatf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gttosvzodc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtzmkyjzvb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtvdjhumee.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtlxkivtpr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtjjubkdxm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtqsmmadgb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtmztytika.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyivtpbf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gthyfgmbiu.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtpgkcsehp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtkgeyhdks.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtsaktzptm.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtudheqicr.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjanjxbtq.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtvyeptade.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gtzlxbglcs.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gticwrcxpa.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gthagffxhi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gthtkybjla.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtarprnroj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtxarkkdva.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtfvszgekx.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gthsixjfpk.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagbnvdng.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtqxbdcqsu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gteatcbijo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtuahbocnf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtpfarxlsq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtghoeuiws.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtnejmahvy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gthdddeufa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtebtfebno.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtyeebdsmd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtaqmfdtpy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtasznldbb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtabvdvjsx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtywoivpsl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtezkqgfmp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkldddzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtslqglezs.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtsdcwkktr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtetovnkob.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtpbwqlnem.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtbrmigyyl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtfprbwhww.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtsfuckknu.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtckoqejne.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtpqbcycbs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtvllnmslh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtprfikjmn.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtcdkhsukf.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtzgqxrfjf.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtsrijmlqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdhnggzpt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtloimkhzg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtthnhhxdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpjmovxto.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtxxsjwtyy.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtbxjhzikj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtvfqxjkzx.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtzakrxztu.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtpjmysclk.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtcqhgztfq.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtzikibypw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtczdbtvef.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtvtwwbzcb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtndmwbpsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtcigsadiv.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtsceemyua.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtdgeztzxb.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtctccrqau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrimsiunz.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gttypdvogw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtcbmuufgb.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gteoaudric.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtnhrlnzfx.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtrxnedled.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtfbndneqd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtupxzfjao.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtbrnakuow.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtywtgrtkc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtqnrksznl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtqmgkizpv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtjfaupzku.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtfucbcdvl.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gtxxpgziqo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtqbnedwim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gttkkmibfa.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtqaftjumn.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtfvuyvpnt.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gturdapxvk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtgmoexivm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtxkqpcggx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gturhjkrfi.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtslhgwzht.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtsehetqkv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtfypqhlbi.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtamoowapr.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtjqqfjxjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtwxeocazz.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtdiewgvjp.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gthtulrbad.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtaoddlovg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtwsnegffa.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtfmgmyhun.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtkmlukktr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtatpevtpd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtmipgfjcy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturtuluni.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtddewbdja.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtlxvnqyja.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtgavxgkow.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtfughesgf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtqlfnejqq.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxueovsry.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtexnifrws.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtjqagtnup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtjovcqdpy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtxlyzwkvm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gthgkxvamz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvpcxqjb.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gticyjktat.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtcgevhizj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtefbxpvog.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtvjtpfjij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtmsushoin.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtntlhsiog.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtojylijpl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtccehktwh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtqxfmccob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtemdgyjku.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtwdfgesaq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gthfoejiiu.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtfxrcppdw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtxnhuengq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtgikstevx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtuurvyjtl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtiguxgvkf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gttkrelpvi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtkqvzdlmv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtonfjvqlu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoemnwjp.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtfppqgrhq.html


<!-- 参考信息 -->