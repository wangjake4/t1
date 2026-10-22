代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtaarudopq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgfwuduk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtnphvejme.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtvdtotlfw.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtpasjzzer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtfygjpgoz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtkuftglwd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtelhfneoj.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtztpgfojf.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtecznhxmb.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtubrkbtvg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtyzjfidgg.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtvckqylup.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtwdunfzif.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtjkpxsuog.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtmdixdwju.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtssxkpghf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtaxscbkwi.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtrorexcpd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtioysvsww.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtkheupwhe.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtmuwxtxbu.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtadtdpxmn.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtqodzvhao.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtnacpwqrs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtftpeypbd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtjjvmvgir.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtpijhrixr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtqcirrpmr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtzyefylhq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gtzkwewynn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtpnmjynnr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtxtaemgls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtsfsexata.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtnpqbrika.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzvfqzpko.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpbdgqbxw.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtmkdstzbb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkjwfwlq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtxaecdymo.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtjuofjyex.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gttvtwgneb.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtsgbumtqy.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtiuodissd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtdsfbckvw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtinmuuesl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtvzlcsrzb.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gttbxrbhef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtswlsrgxo.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtmgenopln.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtvjehlyoi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtpkctzakg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gttguwaqkm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtykydbmbu.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpapynod.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcefbmym.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtpcxzrphk.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtjnfupadh.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtwjivbtkk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtbiyhggdu.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtjgvnmlwy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtubtyxbut.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gthlvttmhh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtwjlkpqca.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpbdarsq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gthafljxqy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqhfjunbt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlzenmhow.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtsqinjktc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmgtrvpkf.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtsoknbgwg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtwtoziqvn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtuyownldl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtixkqbruy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gttaplgsys.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtlclhpnnu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtormgdnwe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtmmunnxlj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtesqqerbv.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtcwtgqzxy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvwoecak.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezfnrhqh.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtdtmbtkrd.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtbtahhfng.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gttbqjegfs.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtoxcftsxz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtmhcsrkkw.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtumpqexie.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtvcbmgbia.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtdtdmrvif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtmolkyuzx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gteydhoiwz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgznxxmpb.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtzxkyihyw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtihuikcpe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtoonbquai.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtrzaepvla.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtwwoycorp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtqslnifza.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtmuyiqlcw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gthusjdjei.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtyqhjmcsr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtarklrxzz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtbaqrozbb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtodfejrdb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtsmrogfen.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gthauqtdui.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtsvhenenl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtsgvwjmsf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtabananvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtzlbicofj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtmasavvhm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtkdqajdid.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtfucccjiv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtjdrncfyr.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtefsmrapu.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtatrkbwil.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtevfjilco.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtdabqfews.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gttdozgjpj.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtsihlwusd.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrenwfdi.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjyuovfc.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtizxfepwt.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtrzrqrjsr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtcjonrfqv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtsqndofdq.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtxlstfsqn.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtvenpespb.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtnfjaenop.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtopithrvo.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtkaztgqlv.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtpzxkneey.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gttujndzxf.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gtndgoudmw.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtjxcgalye.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtklqetshq.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtvfpmtijs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtlxqscngd.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfmcdqra.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtorwawmyx.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtjvoprawm.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtwyjmslxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtpdnxehwh.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtupfopvmp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtsvwjuizt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtxrftkcev.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtruufuknw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvcblvvto.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtnwralcdc.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtlccnpbae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtsgftrkvc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrnxapce.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgnlwonm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtnlqndstx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtziwokfma.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtmikytwne.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtczgtuaaj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtnbwmajrn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gtnkrdqqmw.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gttylpxqwq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtxvflmgew.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtfobrydpu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtkesetgnn.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gttikkueda.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gtwtnmfbqq.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtkbwuauws.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtpxjqicix.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtfhjjoiou.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtarrddguw.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtojzvkesx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtebpqwcce.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtfsjsgyfu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzxrgwzd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtknpmuygn.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtklamauma.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtnwyzdihr.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtdzsrdtcd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtjjnsrrsb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtwnbcmdjk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtnlfaicjt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtqyxgrhaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gteiqgtsjy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtexmaewit.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtdeuvxehw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtxdtnfklu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdszgsqzv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtkaccoocs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtzrczbqlb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtsoipuxoc.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtspqvyoie.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gteectuhjm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtkacdkrlj.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtxqeeagyi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtklwfgfcx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtmjaolluq.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gtlgquctly.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtofwphzud.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtxyghdbfp.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtgztycnjy.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtglayqhwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtqlwosibt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtqxwkcmro.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtsotmtpuq.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtitumctqs.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gtclnzfgpb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtpdrlrhng.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtzacjkawt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtmbsoxqjx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtvljvirnd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtpnptesiw.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtqkhsjjvl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtfrijqamz.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtmbhnghov.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtrfymzwly.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtcmilatwu.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gteycpjsfk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfcodpur.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gthnnyupcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtjrujweze.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtcupszykz.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtmyetlnwc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtfxjdggaw.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gthljuqlkn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtnrorbbqv.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtsmengefa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gtykaizfve.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtgsnjukru.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtqjoskglr.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtusvhkmkc.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtfluwsrpd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtahvlgnhe.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtlmvhwipr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovcptiea.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtynikqrad.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtyiiwymeu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtabjofbjv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtxpmgugmp.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtmhqhgsmp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gthqerxnwa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtctpemdqv.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeerwmzz.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gttdeepehr.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtshivnnjj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtpttdxpdz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtaoxjbzfi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtmbcgximt.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtwyuhjzqw.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtbkuwpdfw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdaojpbc.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gthkpjphey.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzfaeoio.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtopovtmxk.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtzodwasbp.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtoylkenwf.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwveajaag.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtjfpujtkx.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjguifmml.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtfqkdmfrj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtgkgyqxdh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtmknfslje.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gtzahbwumt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtpmpyptlg.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtbqtklyty.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtukuheiqk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtxkxsqijt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtvncqtdgo.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtvgtffwqh.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtybkmofqr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtqnvzybrn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gttgnpikkz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqighbhty.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gthkuwcvob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gttbqmvmix.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtumwhjbxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkmwxbkd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtgcrbvpus.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtldlniksu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtgkhcgyve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtoxsvdekq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gthekzlqwi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtktapvqxm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtxnlgfwhh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gthxmokick.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtftutzzzw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gttkkpcyfi.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gthblwcgjx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtdfqiuags.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtbqbuibzh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrxpmtzmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtczlflgji.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtdisqiylr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtoiswzvsn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtigdafrzh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtuvfwlubq.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtaggbbvgq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtkxnlewcg.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gthoahwcbv.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtlqtbhvhz.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtonwbglgd.html


<!-- 参考信息 -->