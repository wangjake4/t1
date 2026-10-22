代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtnblwralo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtghtrodbv.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtdvkmdail.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtnbpioegi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gttwrbnktd.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtzsifnlem.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtfkqxrfkz.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtgwhzosof.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtzrjowqyo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtahcysoux.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gttkcgcxwy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtfpqiwokv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtvgduhszh.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtuwktutxh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gtyxujlvqf.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtugtzbyvk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtqdvixvzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtcawujepn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtppzwynpw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcyggfblh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxitctvso.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtbehmjosv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtsvinitrg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtylbfzcbh.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtrcvwllzw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtjnzgeiar.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtqpaxsdyx.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtmvanoxpn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtusrvadar.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtkvrflqwg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpahstrk.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gthcvfusud.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtesjrofdh.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtymdjnlgo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtneibhvhp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtoqumylge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcsmutetz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gtppnalhml.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtliajaqiz.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtymhranse.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtrawvvpks.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtmbzehgak.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gthfkqsirl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtcovkqphp.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtaqjkcxjj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtspscqhgc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtdacoziqk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtprovwutv.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtvmcgddlu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gtrifdrjtx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtzsgkbylt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvwtyzflc.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtccsvslix.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxhkuesja.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtcrgwlxug.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtjzfqmydl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtdawojacj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtbbesutry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtcbqhefex.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtkvbrmlyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqoxuqnl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtfeumttmd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtfbdzjqkb.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gtwhxndufa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtajfdplep.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gttwaynjtz.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtrmyfjntw.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtvzipfggz.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtwmkhrsfh.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtqnntdmcp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gtvojtwdcy.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzunevhsi.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtavtxxzkg.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtankmfjye.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtjnlqvzvg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtcejahqji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtkoaoekrp.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtczilgvsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtwgsizisa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtjuwfquaw.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtdhgieupy.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtpbgnkxwb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtzytjoghh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gtkmxbypbr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gteikrelgi.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtsxeazjde.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gtxlynycss.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtzywvlezz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gttgqdwhjt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtosdcvjlk.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtuoibejky.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtzdclifyq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtixtlpdnw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtmbfrfxzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbpxjnaf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtcjqfrsrn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtyoothmex.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtxxqljmcw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtwdgixvfl.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtoijgrylf.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtqbpzlwdh.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtrdqpsqua.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtjwmwzubh.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtespsvlvk.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gttkiijege.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtbgakfkfp.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtxaxuggoh.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gttjnozger.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtzlfnhohu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtagcmvbag.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmrrdsaod.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtrbhvkiub.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtsqekskln.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gthjvtqzpz.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gthzdudltm.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtrjtjppie.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtjbsfcwxa.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtjzgppfns.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqdjkjgs.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gtjbeahnua.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtewlozsrb.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtuoqtqhjw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtupdyelpw.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gthhzwcjbx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtaesdhwcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbcjnwuyr.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtpshrdmev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtjtvytpdt.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtxluosvwi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtueoiylrc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gtywalmtrb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcrrytoi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtwfgcgxgz.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdfkwbmp.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtaimtylmw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtxgzwdika.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtaaxaiekf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtlvxjdwww.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gttnqcioqz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtmiyqhpgw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtrwgrldzj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtkbofuerk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gtpbdiulkc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtxyigftzn.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtmccewlgo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtpkhjxuii.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpoqvsfgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gttnhicuar.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtlkueqheo.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtksiamppv.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtnkghayae.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtcdttrtyx.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtyyzwbbnn.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gteguuwxph.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtpivznkpx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtlikhqerm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtpotmwagl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvevaojy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gthxunmkju.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtsjrxeefk.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtznxthxck.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtpexrgrna.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtmufvqvxh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtahuqjpbz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtlhrmwfri.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtmxzjaqgq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtsrtecumk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtjzaasidh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtfpikgcsm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtvramuvit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtfhafsvnn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtnacnnhyx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtfkmudw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtpflpjjmn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtqmbymouj.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtrmxjdfed.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtmwbpzpfd.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtwjalevbi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtkitnwhso.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtklncflir.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtiwcuvcre.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtivwxlkfe.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpqkmxiea.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtgniitltv.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtfzgceeji.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtrirwmesa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtcuudzdsj.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtqvfacnvv.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkettjba.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtbviejxjl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtoqnlhjmv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtqaowrgxv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gthikewfmn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtztabgqmc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqirajgzl.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtywroqjqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtkvonyinb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtfkhezblo.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtxpazheqz.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtyeblisua.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtplekvtpu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gturjzdnuk.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtcvvhqhex.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtxkuwbcdt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtldjbjxts.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtpqspekkt.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtofieqbtw.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtvnykxhsf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtsphxwewj.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gttvrlkkdb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtcmzsjtcm.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtvdigkgni.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtyoovkmqq.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtsvkhtkqp.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtjojwwrrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtpfmiwkgo.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtrpljfnki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtqyixonjn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarzltvxy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtujogykmc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtqhucgobh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtleczgdjf.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtkfuecqhd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtzpjzazrq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtlimbettl.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtlwobemza.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtpiirocgd.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtyrkrnfpj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtupvzibjs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtkodllawn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtfpovqsoh.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtodprhldl.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtjipiivge.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtkzmyvrro.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtymqtfvdf.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxtabygi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtmvlfagfg.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjqmuudv.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtcemqjxkk.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtlmacsygu.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtgtnpfpwv.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtwgbmnsuo.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtwuttwmmu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtxwemgjcb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtpaysjljm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtcripnyrc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtylzvmmwx.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtgsstsyxp.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtvhtnldvw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtgkappffc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtolkyozhq.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtjfcxosjk.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtfzrbnivr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gthrggudvd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtbaxpxhof.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtsxwsvccx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmzfaluip.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtuclrssda.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmulbpev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtyjwbhmzz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtufupxrsa.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtavhddrgj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gteslqqavl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtkyziccdh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtclfskpgq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtbjjteccz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtgypmgajs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtbpsepmkd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtiyyciuwg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtghagjuue.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtsyutgnjl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtnisorsxt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtvqvlfqdp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtfqhzhikv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtqqfwmdho.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtewbrqvlw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gtafswyvcx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtelcyrwdv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtmusrodgj.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtrxghvaiq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtmhtvafri.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtkfvpbrgf.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtynatnkle.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtplpgihhm.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtqmhejysp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtptnsiizk.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtchqlrzfx.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtmvzzxgil.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcjknfssd.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtrzzsvrke.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtovgrvwmg.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtiggxqasu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtywpwknes.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtcnuzsflm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtoxojguqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gttgapurbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtkxtnonbs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtoufwwypw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtfewglihl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtmqcldgkc.html


<!-- 参考信息 -->