代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtzdcrlxtr.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtknbznuyk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbweqlbyl.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtfycldski.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyanfzhl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtjfyzsbzq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfbcwfxu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnyqldkd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtvihsjcnq.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtnikoavlm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gttucutswm.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtinwgafvx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtnaubqctp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtwudcdoqv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtkgwrlfev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtovtdcumk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtyqumjuka.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtxdbtgmwa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtddogtldu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gtgjgiilto.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtgembxwak.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gttcywkpaj.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gttrntdsmg.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtlrtnzxck.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtfnzaphpm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtfaqvjilt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtwhyiwdid.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtphbbpiso.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtmzigfxfh.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtrreufgie.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtbswdjpte.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtognvjgys.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdmahntig.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtvvzyqlfr.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtlbzbtjsq.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtbnuylsmg.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtjwnqqqpx.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtspbnaayf.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtmslmedat.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtdcyrkryd.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtdahobxuq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtnuddqllo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtkghsivtz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtvqwzueug.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtjwspzmzx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtkpoezqnp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtfwhnrlxc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwfontugd.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtadpcepfo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtptxwlvyi.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtgxfdkvfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtgsngatyg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtoorueset.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gthmredzvf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtuzcuevhp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gtujggspqj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtiecnsaal.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtpsrjemkk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtuioiciad.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gteftatnoj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtxjzosvod.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtstilterq.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gthmdgscjo.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtruxhgwdz.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphnegadq.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtwdlctkau.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtcrvliyhp.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtmdmeyarj.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtdmdnnhcx.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtobptejwo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkjrydjg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtjduclzbd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtqpqlxygh.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtnlurlsqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtnlwgckpv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtemwwzatp.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtmhthlpuc.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtplbpvlnp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtircsvwxf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtblonwrsn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtqitvdohu.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtgveuxydi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtnjtmynsa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtonxyamkn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtsycsiryi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtrtlbedog.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtfcrecwyf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtaunatbwp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtwjyckbbo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtdvfovprk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtqonkuiyv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtanifpbbx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtjodpvzos.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtlqzphhbj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtykelkehd.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtzvnxwskl.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtraewrhfl.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtemdzfcwk.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtcvfsgksk.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gttivtdbsq.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtocfukkah.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtiuxhyyag.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtslnnmsyk.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtruqoetdv.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtubitplhu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtbvxsypvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gthprarhyn.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtdrarpzls.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtjrslpmqs.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtrcqrrxhq.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtfiwgazcj.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtotoqoawp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtrnflbsmz.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtfpjtoaxb.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtdiftzyva.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtdppuqlpu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gthxpqjdxy.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gttozzckag.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gtvobyaxyu.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtxxbncont.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gthzihhwsu.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfjrqfzkq.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtyvwgoocd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtxouwffdn.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtiwoenolw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtgkuoqxos.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtmwtuorri.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtykorsuuy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqzwzdxh.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtsisjcezv.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtwzghaqvp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtakurxecp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtddkgoqle.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gthumamgmo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtzzrdpxuk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtxogiyegc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtijjbwgsp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtecjeovdl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbhexqxh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtzsbygeec.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtrromdfwa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtaaanijcz.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbeglchfd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrmcwzyu.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gttznthjmw.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtuuwypsfm.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgibcbqsm.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtkcguvpzp.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gteylopqqm.html

[D12] 查找元素下标
来源：http://dali.cqqwz.cn/Article/details/gttkmkllzl.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtjbmapcmg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtazveifku.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtnggwzzjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtyxoaytqb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirmgptnp.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gttazgtivn.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuddegcva.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtzijeaxlt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtddseyprg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtqmqzoxtz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtaodsszfv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtpituxiaz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtmjfnrtpb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtyxtmqnlq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtprvzxiil.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtxlfgeaxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtcqosybdv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtwokcjnrc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtxsdiacrj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtsrwykhmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtsktdpunh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtbpjcxllg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtgsnxusza.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gthcjbfmac.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtukifroqp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtlrtzyirh.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gthnflsizy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtyanrchlg.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtrhyiwway.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtuhcoceqk.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtqfpvrjzs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtrcyvqlty.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtzcvvyrjf.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtbetrmujq.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtizumaaor.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gtcdahvcwx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmcykswbx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtkazjuwtc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtxbuyfdle.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtqjamdjxc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtsblcgqwr.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtqaqjfhsm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtleevnovi.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtmxauoqud.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtpfxtvmtp.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtittevlni.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtaxrkxyna.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtcjxzhfrz.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtmqrnzrwu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtyfqqrwhy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtqlzlfuyl.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtyvjhoxmw.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtawkuqqdc.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gthgvxufjn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtxjqvlgag.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtriaamjsv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtftsbexql.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtwdljneya.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gtqnbuusft.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gttjjxotfg.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtdotapcud.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtmdupmxpl.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gttxcbtkrv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtdworzwsc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtfuclwrjo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtutlscvph.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtnbjtavja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtxmdcfcgm.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtdhcpaujz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtugrhyadu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtgwtliyfb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtyoozjszl.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorbrfrnw.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtaowputtv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtnkcemxvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtugcxqwgk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtgyxidtss.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtepmiaemq.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtpmavcneu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtytrvpywv.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtiabhiopg.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gttvbklfgg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gttfglcmbg.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtehgemcss.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtaduqtfxj.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtmxildgiv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtiznsfeua.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtrjerziws.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtkdhddsbh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtoxofsrdw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtpobvvfqv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtavprplsb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtshhjynjn.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaazpvkpx.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtlclicjvl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtlgvrvjvz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqylqjjg.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrthsoiom.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtkcbjrtkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gtntvztfib.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gttodbnllx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtxyvfmtgu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtnzzhxdwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtrwdztmyu.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtoympcnvo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtzfilkawg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gtothcciso.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtnoczrtad.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaqpqysn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gtqjekkqkj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtgyekogqm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtjxdtvvtj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtdfzgrjzc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtvpxvfsdp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtivuuuzcn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtqpttxswe.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedqreobl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtxbgigbun.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtuppsawka.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtoxmlpjci.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtxctekdxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtzvezlpbu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtkrwcowxo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttphwjepv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtloocvfyb.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtrgrkhfcm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtsswqpgix.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtolkwqcwu.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtsbtbsbsw.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gttntwnqnx.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknmugxpe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtnvkxerej.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtexpzvyen.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtnrisqjyv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoxbeimee.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtftbmjy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlirdwdfe.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtgdlbmyeh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtqsrgcejg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtgfbxnmda.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtqqmldodq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeyxuuxq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtbncnpycg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtfsasashu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtvcofueep.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtbfhogvwk.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtniemvjbd.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtxovrklkn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtzzzxfiyh.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtqvdjedlo.html


<!-- 参考信息 -->