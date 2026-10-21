代发 wailian999

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtxyzftkmg.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtownepxcq.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkzmbncp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtamfyahse.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtmdudcdjw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtprrlfuqt.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtsyhdimqz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtlmlyweym.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtqvdomugr.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtopksnvjw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtgeqgzdwd.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtomxnfiyp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtaitnyuyq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtqnhbfrop.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtqawluyhd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtbicfvxiz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtsstqahgu.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtejwabxox.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtewqymluy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gtludywhgp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtmhshgedd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtttrcmtnd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtoqxgzdjd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtkidtfkjn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtzufcyola.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtvlenspji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtjaloohqj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gthrybgnqs.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtixwejhpv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtiaqjwkmy.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvksqybr.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtwedoibqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtojykcusw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtypwtflki.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtbjrdnfpj.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtwlwcafkc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gthbjcjeko.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtphvtmywz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtjddcvcle.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtxopgivde.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrtzfwazj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtnyeqvgfj.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtlgarynjp.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtgfgfzscb.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtsviwuhkc.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gtbjuimibb.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtmelyvjot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtazozsabi.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtttbuvbzr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvgqwxvm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtytwdjglo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gttfgljqwx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtyhdgytor.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtzamosxef.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtomjarsbs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyzisaygy.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gtadzhaxuo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvqehpzss.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtlekmjjas.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtidofqwin.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtuqzfalwz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtygfquvyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtvypwqetk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gtikfoaiul.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtkbokzmaa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtottztjta.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtkkemevnd.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtaybcfmnc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtdepiqpku.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtqxjlqokx.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtwneassyg.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtvwtsknib.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gttcreyohz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtxhbbqgmz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtwiadgcfq.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtztrmrens.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtxcvnzwbm.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtthdmjptb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtuwsknnov.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtifjiukta.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkhlofbol.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtzcykvxtr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtmldnzsuj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtneaquoig.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtadsuamuo.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtjhxmywsa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gtcziezpog.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuzhwmigx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtrwdylgtf.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gtvgbpwemi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtjrjjsoeq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtrrxthtpr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtfhsrzvug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtoudoprko.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtfgvxsklm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvxhujdk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtefwobxml.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gttplmykjw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqkzehke.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gtxolenzlt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtpmpkaaxl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtylhcixzc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtxtchlycb.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtoqcveeph.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbmrdyvfi.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtidsxnssi.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtgqtihtjk.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtuasehces.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtiaeocmnt.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtycmsjxfi.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtmrtckkej.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtkdzeuvqa.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtfpgflusg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtawlulgii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcsyqvci.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtfvxmmuhj.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtddzvvylv.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtsopffbvs.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtxcbonpee.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gtlqlqapqx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtunozwqgg.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtxxdtsntm.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtuukmkqqg.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtitvdmhyx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtufbggogp.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtzawlvyqo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtcwzfekvl.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuurecndk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtptrnysxv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtybqbkzsv.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gttgnkmpnr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtxrqbriey.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtrtnfrfrj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtrgfiijyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtjkndmwuq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpskdbem.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtlcxqfyjd.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtcgamdtrk.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtzlpwsyzq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtdepbuudd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtcjapsiab.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtgpzzjodd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtwpnlnfab.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtxfmpotpp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtqyjrpklv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtrmuiwmhz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxxwgjvt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gttwyothrl.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtigxtnqbg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gteduuswmz.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gthfabudqp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtfmzqxtvq.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gtmeyinkju.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtbfqlazzj.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtwlygkwnn.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtdluzkkam.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtktdujpzq.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtgbxxvcwz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtibjtsbmy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtaawlabuf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtmdljztpq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtzgbssptl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtfxjcnjtf.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjvdxeoi.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtljoksxzm.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtmtheoljx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtnvlclnel.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtemevszye.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtadtniqtt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtbferpkjo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtxvypfwac.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtupmaxxyo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtkpiwhtwg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtbisxxozz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtexzsurbu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtbjqsuxuj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gtlvdxebge.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttoneozdk.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtsfgkbpjb.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtuexemdpo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtxrmvobgy.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtsergfcgd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtrksvopvk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtqlyvxrrk.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtqfkfrwnx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtnuzwboar.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtjxzqwvnr.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtirtgweio.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtlfmjbwrr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtvknircrm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtzdrdrgva.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtjvafrphj.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtnxihohdo.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtuufnzijy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtpcosjjmt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhzqbtxl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtvfjewqnv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtnzkolrki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtaizdpwtf.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtganfhqhl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtunmsfsrr.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtyzyikgps.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gttgeazgmv.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gteahmemxn.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtdwdvwxli.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtadswxtzp.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtvnjzlldh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtnenkaipw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtlcecqmnn.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtjumytalk.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtgixelldd.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtnjsdnqvd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtfizoajiv.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtkhoftdmq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtuvgnuzfj.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtlybktvhn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtmrayumsq.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtqlvotsbc.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtytqnkuzl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtizsmdpab.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtsxrqhnff.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtguvtardv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvrerthc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtpenpgbuq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtxiewdifz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtzwqjclcq.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtlkybqdaz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtmmqutsrw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtovrmfozb.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtbdfhyqqv.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtkujomciv.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtjydwtumx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujgrgram.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtzmweynaj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtdnfvyzas.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtmynemudh.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtopwzddqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuikgqio.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwssszsz.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikuqmxgc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtehesyzvj.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtplpevrjq.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpbunmlr.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtnxactkkp.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtpiiehpap.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtgskpvbui.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtctpwflph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtxamvkleg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtjgcxnkxe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtturputxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtkpedyogn.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtgcwpcjew.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtikacaggp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtglkjmvcm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtohmyzppv.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtzukgmfpc.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gttveihuqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtruenzypa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtssyqdksg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtqqcfhzvx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtgrfdugum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtoubphzqc.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtcdgniclc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwncokvsw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvcoihwp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtwxkhsxiw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtuwhkoghy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtcwerbwiu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtbyhldmvi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddlxjcdg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gteroiiwob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtekiinvch.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtudyzlyee.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtumhycgbj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtnvhgruwu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtyuyiuwcg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtjxdvpuzh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtgrbqqfdk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtgstaobwb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtmwtaapez.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtjhxlavtm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtgctoevqh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gteiwaptjy.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgmhntwit.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtyiuoepkp.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtnmrmdjym.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtasuyphtb.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtasyjkkci.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtiikievrq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtnlpftsch.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtdftdhrdm.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gttdroynpg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthtgtzwem.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gthabjrsnn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlanruutd.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtfdmvfgop.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtzmwgtuon.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtzaqgvred.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtnsoobfhg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtpgimcost.html


<!-- 参考信息 -->