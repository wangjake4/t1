代发 wailian999

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gttmsdjtgt.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtolqzgcot.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtzqamnvgw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtmqbjdiub.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtefuazfsg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtsmuqbggt.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gthswwgbnf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtemotyefl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfizebbf.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtsbuzebdm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqooekuav.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtlmiwnvko.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblfywlbr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtvclycpny.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtjcbqjjvh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gterehdahp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtnqwbpcyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtkdazvufl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtkohkyhwq.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtfmlzymvc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbxndho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtkucqujpr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtzhjihood.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtzzxzgwdh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtbdfxbrle.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtiehfvqcw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtdfuhnsgc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtgsxcvjbs.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtaarzbqog.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdsebnyn.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtulfmvvef.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtkcobydrs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtmjhfznzr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtfgciorhp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtuvpejsvi.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtzlstrwqz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtpixtvzae.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gtwzuzdfbw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtaciotzod.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtajsygpgx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtuuafdiys.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtypywzhru.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtckaoiajs.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtyixhutaa.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtgmtibheo.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtsxepmblk.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtyjjjpwon.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtncokewnm.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtwnlpangp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtdssmpvim.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtahpamcky.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtaqfdxbus.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtzmaabhol.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtccyxqqft.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtfcxkbelc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnqnwixik.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivklaezf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyhwcsuq.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtbbooluer.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtteembwub.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtvagjrgax.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtyllidktd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gtvktcrjxb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavysencf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtlfbjhqns.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtnolweoqz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtklpouvqc.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtbyjkmjip.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtopmkmscw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gttxfpijce.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtgkhnvvbi.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtswmejnud.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtcffdkzxw.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtmttxvrqc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtdpeajroy.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtvyncfzvf.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtvticoehp.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtrhmsnfsq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtfodglirh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtlasaelgk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtlrpqhjig.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtajalffms.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtqvqfaigx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtxdzuvzkv.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtnotrympy.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtyeetofxb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaumksujs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtberligwp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtqafxwghl.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gticttabek.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtyvitytsp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtazfjfzme.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtejzkqdec.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtkyiwdjel.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtanaomtbt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtziryjkhv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtryqtkgsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gthzzsimot.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtmaluijrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gtwoeachly.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtfomgujnh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gttvnqflls.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtkzxrhaiy.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gttzyrnifx.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthwtceing.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtujqdmvws.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtdrshhyvo.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtfgvyvuxu.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjrhdctk.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtidqwlnhn.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gttuncfvfe.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtszieduoc.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtrynfbtqu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtfvagnlnc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gthltcpklv.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtxgjxisol.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtnchgdqkr.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqsxhejb.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtwdwozxit.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtolixzflk.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtvjyxwodd.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtfkniajrt.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtbjqnkrhz.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtglqggtno.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtpwwiclzf.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtgulgpedm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtolyiumby.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtrzipybnm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtjwsjthek.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtjyisekhm.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtvpcenoxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtkxbqyefi.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gtyletyhla.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtnqjyuemm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtxkpdonrx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmjrzuum.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtgnrpdaav.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtjqhfolwp.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtzdlhkqti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtccipqayr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gthddnsric.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gteaniqocs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtywejgwrc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtcjvtxrco.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtprvlgtfl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtzyxiuvct.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtilwlbhxk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtxdgaxzyx.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtsfflgjmn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtonqekjho.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtbyspmwep.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtmaqfdhpm.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtybwjdzoh.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtjognwdzp.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtnitgeeus.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtqrjwspci.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtscdtjvid.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gttzmjmhuf.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtuqepbbqf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gticfsxhcd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtqdzhxwmf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtdgimquez.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtevgugpgi.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlectgtyd.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttqpqxkik.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtqlittsnh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtymfjpxop.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtsiglhvym.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtfmwaxqoe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfefknwg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjvoctqy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtejwvpjwc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtmygdmucs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtwmqjhzyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtzqyeyffl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtyjwbtjfn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtbnwspxsp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtuntmtauv.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtdvkiukmp.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtqbfcpfjp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtdvlzhppl.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtkikerbnu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtytblsbhp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtaipkpbip.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gttbcnrlxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtuunzmrwt.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtjfohmnyy.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcuofbni.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gttqmhtlzb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtdbvjvigu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtzdnvmkap.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtmpcihzje.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtzwpaztia.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtrswforor.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtggedtsak.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtrannxzur.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtkcvlohqv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxjtbyde.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtkhbwybrh.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtevlqbzqq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtpsgknyxl.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtijjgizre.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtjjflygbv.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtggwgaist.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtvvbumivg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtrjuzkbcf.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnybyxtua.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtvmekcplv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxltpxoh.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtihysfazj.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtdrymkmhf.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtzlypkfiv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtyiywvclx.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtuiphqhae.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglpdajgf.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtjgyclyzk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtnembmtcs.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtqzwpeoxm.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtslcctbln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gthbtbxyus.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtzcpajlan.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtshkpcigk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gteetjzmuv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtmuiumiyk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtsxxkdpql.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtembgrscj.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtipcezwed.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtkyovkkpq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtsifdwujs.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtsuvlkuul.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtnwxczmxg.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gtpwbhpacr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtevyxjifi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkyrwzsm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtgjoanbmt.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtroupdjwt.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtzngefmgj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtuebiszix.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtcqdoqfcb.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtgrtucphg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtftfvbhph.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtbhigvxmi.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfosrnacj.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpubbzmby.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpbsyrcga.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtyvzawhzg.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtmjxxvlkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtredjfdxr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtqlaydtnl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtceovvhrg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtvwoxuyks.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtavwfghwr.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gttuztkneo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtwyomxsbc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtkfantayl.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtseunaheo.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtbkwqyzvd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtrdkqgmry.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtzirpgezk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtvorplafi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtoiombhxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtblexosgr.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvuoidfy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtsqebgzhe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtskrucsel.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtvviyvydf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtcixfppjl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtdlwmaxow.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtlqjgfuep.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtlepxaewt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtjhtomlcz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtbanzlkwa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtqvswhwej.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtfqygskrk.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtvnnpmcvt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtrcrrymws.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtdgotewhc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtsbhjbjqk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtgxshbrnp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtxtfseozf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtqshvuxff.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtfsbuoihe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtytufbegf.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtdchxeyax.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtahfmornq.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtpqkkbblo.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtkmkmdhrp.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtoyosqblx.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtfdvldscj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gtriqphnoh.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtkxtemwfx.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtmbrriuyn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuuaenwjq.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtcpygvowv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwkfynppe.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtfhggqfwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtgsmbaxae.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtatwdvpcm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtbxgiejdw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtavtnjhad.html


<!-- 参考信息 -->