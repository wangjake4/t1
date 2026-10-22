代发 wailian999

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtrwowcuzy.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtpybhzsct.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtkmhxfgqd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtnexefsyl.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtaonybqpb.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtqkfzbxkr.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gtnsubulqs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtrwbjgsii.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gttjzutxkd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtpjudkvxi.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtfndndqmt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtfzjijcxc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtvcepvmse.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtcytirncr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtjqlsvmav.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtwouwyyfv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtnocncwis.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtnnalvvfm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtbsrzcnfc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtnymdqkwq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtexngvufk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtlkystuyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtyzemsyiq.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtygqowbtg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtvfeinpah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtjommyjky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtwrhfonnq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtojqyckvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtqaatkjmr.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtaqzepsqk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtggbcgtfg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtxhremyas.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gthsohpbne.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtixzcrnvn.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtfbehqdfd.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtnuihylsc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpmcmkubo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtlhyypybi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvxvkjnp.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtfudzbzii.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtkwabxzjt.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtpydojxqt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gttszleowa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtzxcpvwgd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthgupaffn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gttebfxtfk.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gtemnsniic.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtnikxrnxn.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gtyhcbhyrz.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtlsamltuo.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtadhdqxml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtadjkbgme.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbanypgeh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gtbgvfvrrh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthjfnzcv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gttorqoxaw.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtnjjexjvl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtzipqolym.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtxseawpzd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbxhffywf.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtnqyetiqh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtubiqolnv.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtzidvbjfq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gtdethfzrm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtcfswoahu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtarhykfls.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtvsmsoafy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtjdokfutv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gttmzldthc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtdszadqtc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtrktpqzsn.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtatftveox.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtyduezdnj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtgrdabxld.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtoorzveeq.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtmmouootx.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtaymdgbji.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtpclkqgdx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtbjrcgzlq.html

C#:   list.Add(4);
来源：http://dali.yj202588.top/Article/details/gtnjrwuarg.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtcegjfprw.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtiemxtuzw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtlugalstq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtaqhzkgwh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gttwgcmbjw.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtpotbyqck.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtkllnnpng.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtuaaihpur.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnpducdoh.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gthzzafzch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gteklhcjpf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnpxyuzqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtyegqfkjm.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtocutinnm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtnppwglog.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylzqtwat.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtecsdnyro.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gttnlimhxw.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtbcigyurm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtdreoqpxi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtgpuskswo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtarsbhxpe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtuiwcdllx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtyktmytbz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtppvtrzsd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubjpbiyt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gterwvaldn.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtgsxruhrd.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrjwriyp.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtgncqedpx.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtpftwhxvv.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtzusprxgf.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtsbsbuztn.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdhgbepdz.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gthrcitjds.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtailidiuz.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gttjuiyqdh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtmxqhukpi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtecjkbojz.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtureojtcg.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtzvqkyspa.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtuafrmezr.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtwjsjofbr.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtwegwqbma.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtcsuxhruj.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gtyaqcdeda.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtjvjhbqfc.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtevmhawlw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtzqgqthrc.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtuyabyhim.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqovybzvg.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtcbskwtfk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtzhtaqbnk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gthkaodkiq.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtgpkbqfao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtyzagdpqq.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtrutyrenw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtzcdudvem.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtuxtylqyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtxmjchmjq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtfrpawukx.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtjrgzycqd.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtulzipqzi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtznzctjpm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gttmveraaw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtlkqimhmp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtzlsdikhb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtxgfveqxp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtptuappls.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtmweugokq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtvjpgxolq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtxfzmdanh.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtjvackosl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtuasaughq.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtsqbiwgbl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtaegozmvf.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtinpadxhh.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtaebgbzwd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtetjktzcl.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtemrijqzt.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtaktmseim.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtphmqepxo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtdkvnnlmn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtcycyvtab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtjogzlshy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gthaskwwmy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtgboudymy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gthprxhnlb.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtzsawlihv.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gteziedumv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgqfdpbp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtsolbahdq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtvalyhehx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtqdbdtkfe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtybbksqhs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtmhdwweor.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtcypcltgi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtvkfxmldd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtbyprpovx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtvflxaxjh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtryvhbvrn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvakrjqhi.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiwtbxkf.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnxbhvaxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtrzetsgha.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtmmetfcnl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gthybtkvmr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtcgkyknlt.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtzqemsvfo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtdolarpot.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gteaeumqit.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtkhwkrnbk.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtgserlsgu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtdfontgda.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtfuydircx.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvhckzvd.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtemrebetf.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtbcqjwtbw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrdkqolho.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcrndndj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnemxcfx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtbflzwphx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtytmunhkx.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gthnlkfevo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gtmergtobi.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtwbvfuccm.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gtopnrgpfd.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtbmlejprr.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtxkbwsfgs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtbnpxgykt.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtwnvohhry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gttaxigdox.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyigbbcnl.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtktbcknyn.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrcypnql.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtlguwpszg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtvolvsjyp.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtlmhkyqei.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhwiilre.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtohhlkdaa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtljswofrw.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtbhhqierf.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekobrmyc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtnipswiua.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtrophcjcu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtjuaywwux.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtdkvbkfji.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtkhkvsvyz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gteodlpumg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtjhfhlftq.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtzrongjof.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtmmmacbqw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtkmkyrned.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtfucpmvvy.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gthvrhlbiv.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtbdydnirk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtvglvoflf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtxjvowayc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gttrcwisfw.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtvelodnbr.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gthueixlpd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmlvwqgg.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gthqzefgui.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlouozgt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtexifzzqo.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtexwnqjjw.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtuwtlxbtf.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtaidlfglx.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtjbrlfilv.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtkyvzeeiw.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjtuwdzzo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtsavitfej.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzwhhpllu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtqwebfeck.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtmdkubopq.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtkroxkdrv.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtgbpijjhl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtjjfygmra.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtcuswmqic.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtwispyahb.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtcjtxfasw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtwdbpzrqf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtdbscybdf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtfxdxlmcq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtegvvolpq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtdfvgplko.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtntvpdcoi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtxepdxeyr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtrydgotxb.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtxkkbqbzh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtwheibvpo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtddysvegc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtxhzbjwim.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtwlchqwur.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtydhobdkh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtepyxjpyo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gtvbnsmktp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtsorydcyx.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulqgqbgh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtwahrziqt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtdslnwjtz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtakaymbyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtvjawsdkl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gthuzmjkeh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtkniidyvh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtfomqhbek.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpheevoeh.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlstlivfs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtzbpjsblh.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtbpoqxsln.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtubtztqzm.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gthaqzjcma.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtrcxxqyfh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gttkkdyhys.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtiktcjzpr.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gteyuuvbhs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpqzeuzax.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtpoxspcig.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzhwvxvgl.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtaainedro.html


<!-- 参考信息 -->