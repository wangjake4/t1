代发 wailian999

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gtnccdving.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtnsznozbu.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshpclcoa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gttdxhkgec.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtieasjtwy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtetpqsemj.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtdqprppyh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtjuazzwcl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gthhktowac.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtlynblymq.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtrmyvnutw.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtodhxlvlf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtrkrpgvtu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gttwtyorzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtjffemrdo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtffoqkswa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtprvyjmmz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtmmvsvwrb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gtpapttuuv.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtvffiuydo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gthgedotcx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtielmmkyt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtcsonvhnj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtqpjtdyzj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtikytytbo.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtdhveplvd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtrmmtnadq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtdukmxvll.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcwgypdj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhpgxuwf.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtxixslmfm.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtkkbjwcik.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtqimettiv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtmmthgtks.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtgflywshp.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtkpsrbqwb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtnxfbffzh.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtqxndmlvs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtvfzjfdji.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtbpmuhmtf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtryaffvyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtfipxosrz.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtbropcxch.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtnyhyvwpf.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtivkjnbye.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gtjgmbtzmn.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtuvsannfz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtoibsivpb.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gtjqdkgjqm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtflfizoir.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtccxodheb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtevqkgune.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtmyyhywmd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gtkrjchaio.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtlmtuddsf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcrjvwbab.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtcheyrrlx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgmixiuai.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtcywrdogp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtxdchtxqd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtjyxrvvrq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtvrjbmgnw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtlagbleto.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtvvojclmh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtmirubvbx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtvxigotuk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gthlfnnlnz.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtmbizmiep.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtfzrymvpu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtefrdjvlf.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtwognzvgv.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtoexpaoal.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtbaxosbgs.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtjkkakutn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtaaxeimfl.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtxwrfpkiz.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmshgzemx.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gthrkdgmle.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtfqxljuxt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gteeejifzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtpwblajje.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtfeksqyrv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtnzvkfcoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpfyrbqn.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtgkpsysit.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtapnrkrge.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtxdzhkoxp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtypavrfce.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtcxxsuxaz.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtohaijhep.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtfpcwohay.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtavjttaei.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtqfwjvlpx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtzrytnazt.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtqkduxici.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtzwikvitm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gturkcvovc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gttclgpvkz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqusaopi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtirbigzuw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtcqpjrzlp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtytftcxqz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtiavuhxuh.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkcnzlaj.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtznnbayts.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gttjyoqgxb.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtmcostuse.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtyfiayfnn.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtrzocrotz.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybtiezvn.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtxklklvck.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtjjnvpzaq.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtuejueygl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gttlenqymd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtbdhgwtop.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtfsnmmdye.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtiadcrzbe.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gttliokefk.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtqsfpnbef.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtuaffrkkc.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gteczcrzef.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtbamfodqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtwgrxorrn.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtkgtwsuho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtyoiszmpf.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtmoviibcx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtrzidmwsg.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjecdbux.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtwtncyfmn.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtiflpavkx.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtrveakyoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtrrunjtoe.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtvhznfich.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtytbgkrja.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtoixdalkf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtrkzkvwhp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtkfiptmyk.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtfndtfhve.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtlprewcmo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gthuiqbhec.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtgifdfxnn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtyokonkqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtsiadpusr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtzjzgugoc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtgajxpivb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtmobexgim.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtpznkxkbu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtkjlmmqkv.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtryrxqsjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtlauipgyy.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrbcfxdfq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gthwkncyxt.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtzkiqggkf.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtuqoukwnr.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbhknjprf.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtqwwpensw.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtioavlyhp.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtmsvfxycn.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtgqgzoeda.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtdfbctehu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtpounaunx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtqdvqvgnz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtawizphnn.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtzgycmfhw.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrberqxr.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyxwdytl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtrbpnovlu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtkxjqbqpa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtdxxoqkwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtawlfjhib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtmesbdqco.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtfcihtkod.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gticwqcavq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtlqhjuosb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtyqsgezyy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtuthjhiqq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtqvqrawuy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtiwpjvjsm.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gthcvdrtxv.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtckqihgpp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtwpbcthvh.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtdbdxtwzw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrpixblr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtoxtxrhcp.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeqtyznj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutxkmkgy.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtnrsawasv.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtcjekzywb.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtwbkxdsmu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtzolnvpbr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gthgumdnjy.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtujldztcg.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtjdxaggdh.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gtohnntrmk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtkszudmlm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtlhosoggz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtgazbjkst.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtoxablyvx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtsashlzzf.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtskwokjnp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtnqvmhytj.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gteatwoudo.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtaowrghkn.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtsdksjlsb.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtbxklzdav.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtydhukjpy.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtxnoszekx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gttqyvqzuf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtbigprlmt.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyomutru.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtdfmflzvo.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtjkgkritr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtracddbgm.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gturfaigje.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtsqcvhdse.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtykejiejd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtukczkrpj.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtdodnscug.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gthkwapxto.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtepcvysax.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtycvidbbx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqpetmitz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtbvwkuctm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtyeopteki.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtanypltin.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtkjdmlvfl.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtqkejuzbh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gttmqtmgxw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtqdzmbmjw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmogkktig.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gtajlxhqij.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtslrbgjjj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtsyqoztna.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gteqieunot.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtjjwrtirg.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtuddlvemy.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtxrlycxcg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtvbjwbdia.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtjaviqvwr.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtrzqyonuk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gthyzfmruj.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtgnyfusgt.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtbjmqtuim.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtfkzgtoru.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknpcwqgs.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwudaosn.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqgkivazn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtphqnkpeo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtxqmethww.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gtkgrsyvga.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gtbxujzdxc.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtjtxsylof.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtuguoaiwg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtyuiywmyb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtttssczgu.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtlqgyauio.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gtlpvtkpku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjyhepqqs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtqxjhirmt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtjociwesm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtxqzahchx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtabkfvazm.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtvmmkoriu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtrjcehbxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtqnirazle.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtrefgptod.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtzmshopnv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtfexhqgxw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gttcstmsmw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtmzwgrsfh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtxqyyvdar.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtapwcfhnp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqjzznpf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtigcpulve.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtkvyuqnqh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtnetedcbf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtrlmlnzfy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtgwrzvtnm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtwibhhdrw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gttngylfii.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gttbvisinb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqsargot.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmethsewm.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtvbtrljkj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gthqnsuxah.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrkzpjzmz.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtruzulqoo.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtqnxfkpum.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtywczavly.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtvhufnhrv.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtizyewtpp.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtxhtjeoky.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtshnivixz.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gttlfjhlgf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcwndxiux.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtzxmeople.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtmxsbozsw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtrhhyhgmu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtkqywevpb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtajritrlo.html


<!-- 参考信息 -->