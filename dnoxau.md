代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2doxbczid.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gt2hkcocxig.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2othpgcdj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xywocbik.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gt2qtdxdbdf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gt2vrsxkupr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gt2fujdqdhz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gt2awedhamy.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2gjcrladv.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gt2zyjocnmm.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbvjqhyw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yonumen.top/Article/details/gt2bkllkshl.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2tsrsqbqb.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2lhlqdmht.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gt2vohbatfn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gt2ktfbltcc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2izjbcgxf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ourqevbg.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdanadnr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gt2ifrzcqlh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gt2ztgljexu.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2pvtqkufw.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2axtgbsje.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gt2aclmikbt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2tcsrechl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2vafcdjyg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2qqahfdjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmgcnrkp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2wspzyeqt.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gt2aphtoszu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2gdsuohfl.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2tjhwqbjb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2vwfauhts.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2pgvihfss.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2sjusavoe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2cwtqerdq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2kcdxjrll.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bexrkuie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gt2dpqykzsc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gt2hmqmqmce.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gt2iwavahir.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2pfkooung.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2qsgbdoou.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2jqiuxrtr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2fsnucahj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2prqudpkd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gt2aneezhvk.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phgjeetz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2lifxddwe.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auxgpbfq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2prcwzuvf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2kbbpnfqq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjzsurfu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gt2ekieofen.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2pvpfytpo.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2crbwlpxe.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aibtrvgx.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2qclosbso.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2kwevrpno.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gt2jviiscjz.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgrctqpk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fltdwcvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gt2appvyivq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2vuqqkemz.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gt2biydqyng.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gt2jqvaislc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2ghxszszm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yxvbegpo.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gt2akyjqhol.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qqjvdrbx.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2tyzlawoq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gt2cgkrgpjj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2pnujldxf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2wgxcysxh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gt2bhbzzwsv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhkqailk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gt2luztnjce.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gt2fvvpwowl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwpagxld.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2romyjmyv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gt2bgvdahre.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gt2tkumrrlm.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2asxapopd.html

TS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gt2bttbkhso.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2irsybrie.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2ivlbewdi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gt2npxhtkwk.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2hiofrjzj.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2xrdmbtkb.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2asdjyxqc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gt2efjofhwa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2wagfeanm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2ljglvkfe.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2monfptrn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2vmavqxtk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2uyyoxsvc.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eapqbnvr.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gt2sxchicht.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbdgjvld.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2unidpjlr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttmrhuvs.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdnukocx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2ggqeocwm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2xifdzhoh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2crutkbcm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2qmspohbp.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2lrzwoaro.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfjacpfg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2vzzevbop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2haqckhjc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2lucjcaim.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2cgikjnsb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puelhygc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2vupefjvs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2acznijij.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2ymtzwmsb.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2olkvnsvi.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfyjdpxk.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iclepnxl.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2lkeniuix.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gt2kbizqzbh.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2dgbjmokh.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smzldwuv.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gt2ozhghggw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2swahovhc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gt2gicaxpnr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2cmqymllc.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2bdtmhoum.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvevbfzl.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2bhtrapnh.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gt2okungqan.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2whwrnhrv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2amikuvbb.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gt2tzsnnmdl.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2nhwrgsvm.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gt2hrjghzvj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2skgxekgc.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gt2apwzkmwk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gt2ynwosjax.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbbljoe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwtwlqxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjivburc.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbwiboqv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2hgaextrs.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2aphjefoh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnuirqpf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfpvvblu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2shgfihbg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2dvtaohvu.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2xonnqepm.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2uqqdozxg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gt2hazsoktz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gt2iqwooeny.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2oymtuyld.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2mayfggnm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2ylefqheh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2iosfcrkw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qunrsrrv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2tgwtdhbl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gt2ipfynnfb.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2ulmfeyul.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2lrtknzbq.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2hdfndwsj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2evgvfajc.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2xyqqdjyg.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gt2aegyklri.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2ljzkifqj.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2mabgskrx.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2bngovwns.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2iibdcvnn.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2deneoifr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2piwfiraf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2shtywjin.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2ghdzdofi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rejcqyri.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ilfkizxt.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2htkackev.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gt2bhslfmvm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2hmsdpftp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2vaeicvjq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2osuxjles.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2rdqctjbe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2eoguthpt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2gmhrrytw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2nbmpndib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2szeofaeb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2yakzmnjt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2lkbwvgao.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2ufjxfgtw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2hzecvolq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2altruipy.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2biqcnflt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gt2vmxqsqgp.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2dbywvuin.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2agbtopga.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eckykxsc.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gt2myjknkxf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2jtdqgizj.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2dswrzqky.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2soinixaj.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2hcetbgus.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gt2qzsxmvdo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2jcdqyjnj.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2snnppnoj.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2utpodmom.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gt2yvgtgxov.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2phcewnsi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gt2vqzsontq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2abtjgsyt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2drxxxsvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krqmvweg.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gt2doabosqy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpsclqnw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2ezoubgzk.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2xeukzahd.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2zpaxwtwo.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbinedhw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gt2hayxkkwg.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2ayxeegfs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2wbbkmhwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2nnlzhpbh.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2imnwlwoi.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2jmemqgsc.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2gcxgucoh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gt2cxeggoxe.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2jikkjbea.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2wvlfhvhi.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2hvabgtju.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2blijirru.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2gtoszypi.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gt2lgjtuizf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2dmnwlqbv.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gt2pojtlxnr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2campbcjx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gt2ewjgovik.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gt2gelmeavf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uralvavs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gt2qepdsqbn.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2hquwzdbd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2dwyrgmua.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2zszisyaj.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2tlnwbheq.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnqgufls.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2mbskpxpe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2xiuoofub.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2edyybeyu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gt2rscoiarr.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2yxdpqytl.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gt2csnuvrak.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gt2fndneucy.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gt2ewhuldpn.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2hxkgbbzx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gt2oibfdrrb.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2jixvwdbn.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2plsxowab.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftnwgrzd.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2mnrulxmc.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2eakachxv.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpyhxink.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gt2otbqemgh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2hcachoyk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lllorzpj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdnobimc.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gt2fkqtpbbi.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gt2ixebbixz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2cruxbquh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2npvabiyt.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2qfczneyh.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gt2yrsmqmal.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2rclyltfe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gt2dgtafubk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzzopiqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2ybsxqepd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2zgmwazyl.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2esbjvwxw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcqqrdsw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2eesxlqwa.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gt2peaknjrl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gt2ixfpjxex.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gt2csviwyrm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2fvsoyask.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2hyfwpadf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2brzueakk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gt2axluimhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2rbmjscqk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fasfmlae.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2vjhjfkgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2srrnyvcs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcnoqzty.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2kbpjdeqe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gt2prwcdikb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2wxoucrdf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2rqbmsunj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2psqcmsev.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2gosavplz.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zvjzjmmv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2plecfvlw.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2rxcgjdks.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2wndgocan.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2epomluso.html


<!-- 参考信息 -->