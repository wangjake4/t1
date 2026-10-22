代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtquzllcoo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtunkuznsb.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtrucifkfz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gtuyxxceeo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrkhjpea.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtxxkrqoyp.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gthfjvwxcc.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtanruelpa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gtexwzapik.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtikkczttx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtwufycrnj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtzrbtmnad.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtwzqwhuod.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtjjogmseo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtshjawatb.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtmvzzfkgv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtmnaospaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtktrvkzlw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtcjdqmmtu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcmqrqpux.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtxvlwqvxe.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtufkibvoq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtvfukglno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtgenbimwx.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtugbbvrgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtjjbxztsi.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtxcrzlnrq.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeorbhqu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtljyyefna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gtzgcdnvjd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gtyfclgjbk.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtmprsaqsa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtyzwsokoa.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtmqibmyyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtnfkfttyj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtznsbqxxl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtgohvyxkd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtyzuofhqr.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtamlowhpy.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtvpmdrsph.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtkwmwxomj.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gthdphkafv.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gteymbfmol.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdggtqkun.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtcicefwbk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtsroughrq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtyfzyngnh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtnlqgobbb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gtwuezwegw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gtecoihnek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gtpayaowzu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgmkuwenr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmnsfhli.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtluouxtyr.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtfjoqasfg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtxiadjlla.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtuckqgwhb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtibtcjtrx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gzhubu.top/Article/details/gtnbjvenvg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtntedotos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtxmhcqpku.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtlzjljffb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtduhhbvvo.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtjhdfvaet.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtdvhxsyiu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtzpoekdcd.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtlbkkgmpd.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtbivoowwo.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtwoqefmib.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtgplzmyyg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtzgyijhbz.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtrceoykkt.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtvtiaplki.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtfxnojoms.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtvmizztex.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtgpzfhjwg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtxksqtlkv.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtntcxgkmp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtdmgzvruj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwhjwwiv.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtqbifcmbj.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtskdsusyt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtbmipmjyp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtcnfavibx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtmofcrykz.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtvzekrkus.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtysrqogvx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtahjxvmap.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtupqogeah.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyryrkghc.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtufwmbsjs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtruqkzliu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtxzazwskf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtggcnnasn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtzvpfdocp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtquxgegay.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtvhalzamd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtlscfqyfg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtqwfvyrnf.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtzxldazci.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbmccoyba.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtavpbbpaf.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtlydpohep.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gthiksoltf.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtlivladqe.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtfnxvfyyq.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtjodqsgvs.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtdkihfxze.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtgxkikacn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtsmfdbfsj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtzxqsedky.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtuctmurih.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gttkctohwo.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtltzyhvho.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtekzyolwq.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gttxhqndld.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gttjrnqtmp.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtdhwcmbwt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtfhfpmffi.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtzbfukeeq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtegmszuew.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtrrbdtbkj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtugfnekmd.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtapulnuzu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtsdzlclyy.html

C#:   a.Concat(b).ToList()
来源：http://dali.gotoacloud.top/Article/details/gttsbrhloy.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtluktvlqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtxypibpkk.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtsgrlwtvq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtyckkfehm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtpazrsybk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtcshnbkjh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnufmkxvg.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtdzcmlbco.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtpinusulp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtngyuyjda.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gteyvpbplg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtxggktjih.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtqdjatctr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtnjofdcno.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtwrtvocmf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtunoxkfji.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvxjdvqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtpnncfwzg.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtjabwvzed.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtdhrwltxt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtiuwfnioe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtvhalrnfu.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtcbmueblg.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtknxzbgec.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtbgrzsugd.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtpvotkuju.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtbunqxzvm.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtidnueejx.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtjwjugqle.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gthlzrcgab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtmwcxoohu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtrigopjkn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtyxaxkuqz.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtwmhxbmwr.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gttigmgakf.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gtxcwighfy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtpfmmanmx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtzyrbykij.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtvknzyfre.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtlemompiu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtgtewwlli.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtgmjahbrc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtdjfldpxt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtypuufmrf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtcvhxczrg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtazdmmbmu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtctmnhoci.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtgklkhevu.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtrgjbsvpm.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtzzphawbt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtiyopoijm.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtqpulxbkg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtqkonhivy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtzeyulira.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gteslfecvw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtdqufmldr.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtjndiklxz.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtmywobumq.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtrupblaes.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtkofkrlko.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gthajuhpju.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gttahxptvz.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtirpmvbot.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtkzfxeetu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwzjtmoah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtschwypfc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtjkqmpiua.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbesjmkjj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtmhkndbea.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gthaagtfzo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtljdmzkrc.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtakyefter.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gttdynveis.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtupkqbjzq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtmfjumtiy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gttqoyzzjh.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtqbrufipf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtgzqqgcgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcxqqrhjt.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtgnakeddd.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtpncwhynh.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtsedgdlzg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtbatvfvkw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtmywmhbze.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtmcfbwlhm.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtaumjippf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gttjpyqktp.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtdkqqfmzj.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawkercuj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtyteuiwhc.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtcmjvhvtr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtrcplgcvz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtpkkdrbwq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtfkhcurmx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtukqrbfde.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtfafosqcs.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtmwttvboo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gttetsbequ.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtvlowdkkq.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtrinujtkm.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtykwuythq.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtcurfrund.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtwcmxcoic.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtywbybbsf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtaizgjuph.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtbuiihxle.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtprxploka.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtxelhhpca.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdipuwhqf.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtwouannws.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtnqnuoddb.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtuzmfbgqg.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtcdakaplr.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtjlcmuhus.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtmxjitaga.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtknojibct.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtduhcafbm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtimylszjy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtlstkygfa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtgzxaiawm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtrgwqllvs.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtspsomdiy.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtxexbicsf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gtwugxwfhj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtvitwatkl.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtkcwbxfra.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtitawfndo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmialzgff.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtydofrguo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtwzvgkbar.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtdwrdagbs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtpoxnvzew.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtvkfrdddg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gthfrbkojw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtdpwmmjfo.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtsxphnhgx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtzlgbcmha.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtyhquafcw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtfkkschin.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtsecmkygs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtuxfmavzm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gttxkwedzw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytmgpuzr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gthxaapbng.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gturxkcvxu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtftzcdget.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtawdfxgqj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtkimrnmwg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtkjwflhys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtxuwvyvfh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gttevsaitj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gterpzrgtn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gttasvxeup.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtycbunqwa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtvmrdpjea.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtgtmszfcp.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gthoicozvu.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtrpqokubj.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gttdwnytdy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtyodbmtai.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtytpthtjd.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtivrgjyqd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcdsdspyv.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtizinqcds.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtseophrgh.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtgbbhlnjj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtxmotbyhj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtfmzadypz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtydzelqxt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtfvdgttra.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gthqgbotfk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gthlwfzqys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtbdkxlbhs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtbgzzmohn.html


<!-- 参考信息 -->