代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gteakwbwnx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtwaqqigvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gteumzvvab.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtwwltqave.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtgpshxlsi.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtvophknfg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrecrpipr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtfrtzacrk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnytoktqo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gthxskhhpn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtnjkpakpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtcdzrxfwe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gteatlrjvf.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtyezczbwc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtfoqifazn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtimxrhfug.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtmihayoxk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtpxnaumjw.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtzasbdbdu.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtwozoxhzw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtlytmftut.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtxotsogvv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtkvcccibs.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtzajlcvaw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtiqfyvryp.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtjhpedgbb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtvzrkxoog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtmthcuycj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtbqlixukt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtbcqkaakv.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtmofpixso.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtomsfnkrh.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtqbqvdeua.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtovfbsehf.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtqwliuwll.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtoeqkvxze.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtykjbywmi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtxohmfjsi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtvguzjtmp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gttiskvoah.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtfdocbana.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtsydpbyuk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqqwabhqx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtclzblrkg.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtbvnkbhyg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpfnyvdus.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtyxncifkd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaipxmbru.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtrclherzq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtdoomixpj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gtfjsijzvu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gthvrjbwmu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtnfummehj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gtozwgsbjv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcryidntl.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtuttcrpha.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtgwlyvgmj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwjkoaoj.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtlcpiudmf.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtmekyjxtu.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtpygnjkqj.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtoketfmat.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtyqcmgjqs.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtkkylnoyu.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gteerrnaey.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvrdetgji.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtmtighlbe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtaoufpfpg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtetoouqxm.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gttlipwfnb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtmxsvzfpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gteaizwojj.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtmktyxdxh.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtbjyoztcu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtskxhbfjm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtbfxgotnl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtvnobcdpx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtxzlrbprz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtcblaunap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtqlvfkfwg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gthxzvzjel.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtygbwbrwp.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gthllojfev.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gttrnnbejp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gthkvlkzhq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtoyfzqblb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtcbgyldep.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtnctoscvc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtlaxrbxnp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtzgdikvjt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtgiozyxvf.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtzmowhxup.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztjsjwvb.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtknodmdub.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtbplbbcyv.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtdprfshcq.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtugmbcobh.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtpopqdtnz.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtoktbunmf.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtrfogwcxq.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gthkfgjcyg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtedcuovbi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gthyaoisog.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtlwmgepyx.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxeevghk.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtotkevxqz.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gthfbccujy.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiifkxob.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtpdxefquw.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtttxldxdl.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtqnzghntd.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtbmsfvuti.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtqieqqhez.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtnjgubruc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtbwxgrcii.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtfnaxixla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gttmcvjusv.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtlkxdyweu.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtplcwozeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtadduptnq.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtpyqyqsdt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtnqvfagvj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtfehvmiqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtrynxsknr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtitjasqly.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtnjembqpc.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtrpumxxrz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtmupmzpsf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gteoizpxrz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtubfoxvto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtzhdgwbxt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtgjuvlsqu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gthblbugst.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtpdmxxnjt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtmifqqxrj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtidjbyphb.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaycdqnun.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtneykyujw.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtmkwphidx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpauvfeu.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gtnaoesipd.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gthsjkzbic.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtplcfxkxn.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtyzcfhpxc.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtsshyvqkx.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzyxtuax.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtvklhtows.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtjbcntzna.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtijlpafpv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtiqjopqcs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtmpvxioja.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbquybof.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtzpexwevl.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtklhawueu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gttxwizhze.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gthkbpmonx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtmklmizfr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtjwdnubxp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtkyczcsfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gttkekyksj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtlefprihm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtayphfawo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtgkxqbvba.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtdbwsxdxf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtuioybfwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtribfvkcm.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtlweocguk.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtxsyairaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtlfmohndq.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtgowoltvs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtwsegosrc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtsbegwsbm.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtyanwffso.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtrgbyxhhf.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtiiscgmbs.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhkxqlrq.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtjhwollgo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gtmkpdgrii.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtysdxycng.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtvcqmneyc.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtvodykhpk.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtpnhjuyxq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gttivekcri.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgmpwvvp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqiphawtv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtghldycgr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtvauebcst.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gthikbagfh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgycrqaww.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtpkxeiezm.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtmbaelgtq.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtmgkmbxjx.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqesafxjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtdlcuvcfe.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gthjnimwrg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtgkaalsec.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtrzvlkaod.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtjlncxrqg.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtiqksjdky.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtzjsmxwws.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmxmqxht.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gttbcclxpp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gthpnadlbd.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtvqcwkvua.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtmdkczbzg.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtfrwijaer.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtdrtitclp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtqrrdgyjb.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtmvtnyuyb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtcetmnbdh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtlrzbpsgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtrhltkmei.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtoupwlzwi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gthisgmgii.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gteohpbjom.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtpgkrrugd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtfaihcpwt.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtwddpcrre.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqmvaprqe.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtdoaxlhfp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtxcuyzliz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtactnuljo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtsygbfdwx.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtmcttydff.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtnortdnvf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtaxlatvot.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxngxnhyg.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gthiaflotj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtjlrnoqvc.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfdiepceq.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gthbhbbeig.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gteopwzzqs.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtvblsdboo.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtrinagenx.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtetcokfmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gtfeuelfch.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtckaqzcqc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtpuesvvch.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtzwddvinm.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gtsvrmhtio.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gtohlsooez.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtqsjmvaqo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtochvowhn.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtaymwtwny.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtauuqhfcr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtgjrffbfq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtyxccaenb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtuyeqkryn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtpynagjwg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtkbycovdr.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtnuollahd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtvuywrljq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtsgmdrqau.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gttgpgsbpe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtcituercc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtrwhcirzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtqsenvxtl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtraspiptm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtujrrbgxr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtccqgzytp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtledwctpv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gttxtotsod.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtgouqndxj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtvxtmkcdh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtzsmznfkf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtwtjcqluq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtoybjktvo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtdoicyzja.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gtduhtlmnj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtsabinhpm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtyjogmtir.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtpbuxzgla.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtqlnmyxnp.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdutwpqte.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtwoubwytx.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtourtpkee.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtgemytuuc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtbmyfrejv.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtgyepqnze.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtfgoxqrgd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbzgrbcrr.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gttraarylh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrovrgzgf.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtonlyxrmd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gtuacubmta.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtoiwcvzoi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtkrpppvih.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtijbfinlu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtjaasmffa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gthomfqlxg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtybmbbnik.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtotbttoje.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtahnkgrwd.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtzsrvtcfs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtbsvafcaw.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtwshfcxrp.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtgiwpyyno.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtspyypsfd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtcpillyhy.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtruevnayz.html


<!-- 参考信息 -->