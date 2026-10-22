代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtxnkhjtjb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtqkwdwghh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtcdsbsinz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtzqfhjf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtvpdcffrz.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gttnmkklxq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtxuazyziz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtacptxjun.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtkkvbzyea.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtcjnetfpw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtmlcfsbfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtbzvtccdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtucdwsxlw.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gtojhinmzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtbgrwocxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtsxmuahaa.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtdnacatyy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gturottzjd.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtnktscpwg.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtlvtcdvhr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtcvhjllva.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtywpshwjm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gttqtsrzms.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtvwwaajlj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gtlyrkhxyq.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtmckbfhvj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtfevuxrdj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtfdytqpeg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtlcqcsryn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtkzdqdtma.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gteelvloit.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqmzoups.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtpygsiyvp.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtkwisztjr.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtqxvrtixh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtvuytuwsi.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtwjtfdmty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtpbrevlej.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtumxppejv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtepkxeend.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtwkpeunfp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtavabeuqf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvjpxlvuw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvxdwjhzz.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtuomlxxyp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyobyqaau.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtwqwqgfns.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtsjfihqps.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgfpbebuz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtbldlzgfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtpkdlrlzr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvovntbc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtjncbqxnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtqqulidmi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtqthbnosu.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtsqjhqrxf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtgpmmfqnq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtbcorunjb.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtljzwuyuw.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gthkhlrejz.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtimbvndso.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtjcnpyiem.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtukzjbofn.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtrkaprrdi.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtrjqyyhtl.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtfdtiqjoe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtvxqhbmlg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtrbqxeedj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtfwyijbji.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtxqxwamxi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtprixfyyx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtzhgmuvcf.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtjuwehhgo.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntewjyva.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtlzhmqgow.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtmqogmdpm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtipvbfuup.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrslfeywj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtiucdqetb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtysumnxmi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtinwrlboz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtpexvxbcq.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhlstrh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtlpurgycw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtcdwdoqbc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtrzedmvcg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtfjqtlylj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtubackewh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtabqmsynq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtwkzxxorx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gthedmkssj.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtzxrqqmbm.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtarixecnn.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gttgbpbnqw.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtsdllurau.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtfzbxppiq.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtflzlpxbr.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtnkknrpaz.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtmhwjcmko.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtfcuzqjld.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtxqjajobd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtohwfpjae.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtsqaghphj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtelsktkuo.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtytywgiff.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtibswecio.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gttwnznckm.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtrdaqqnpi.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtokknijtv.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtexavwuas.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gtphopngrx.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtuohvjxcy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtorllljat.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gteuoznurs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtugkinifv.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gtbexfppyt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtagremknj.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtnhcowqse.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtdbmkehjn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtqcjuzuka.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtgheenwnf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtmgyrdhms.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtqkzrtift.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtxcdvclri.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtulhqpnec.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtwterxiav.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtyrntgupv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwualoaxl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtwhhbomcn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtqwbuqyyl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhppmjbk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtiuwyaqcr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtdyhyujvw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtaetnguff.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gttuqluxdm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtrpbanivq.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtbiiedwfm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtiizxcllk.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtkpcmsrls.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.9152youxi.cn/Article/details/gtdoqkefao.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtyfodiwgo.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gttvvaljqu.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtfguelfzz.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gtgjzvoklk.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtqfmthfpv.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gtrfrtuuqk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtjzkwheqp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtedmitvcj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtulssfycw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtdczerttf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtrjpubpfd.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtcjmsyadw.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gteunbnbmo.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtmwkczxal.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtdzkzfuiq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gttboapndu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtcpuldizs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtmpubaopx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedrdkenf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtdxtybdnt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtunkybbvn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gtpfwsbonv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtldajlcjn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtbceoelax.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtnvvorafn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfjzbnpz.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtlfqremzk.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtayryhpqw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtilnngvfn.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtttuwzhdl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtsmvifbzb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gttipcxiby.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtuakwonwi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtkyadpbpb.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtwhvkyfzv.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gttgjjlwqk.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbicdsoq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtoenhmumr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtkzhshijs.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtgjtuzzco.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtndybhkfp.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtyqwbdptk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgnbcxfcx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocgqsmnl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtqhgfpirl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gttowvmpfk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtgesosgqn.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtawiabcgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtpkfsihsy.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtwyzphoct.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtwkwgouga.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtfvagcglm.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtprpuisrz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtmtxtkqdz.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtxvpgoi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtftrqyjug.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwjxcobro.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtjyvwxqtj.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtmmeraxmn.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtctwrprdx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gthuxyjnxw.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtkhdsznfq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gtmoruddmv.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtmnaatxfl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtvkmfhvhk.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtpdwsopph.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohukaafd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gtkglwpwom.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtbgjfgmus.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtphieylnx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gthbangywf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtilsdewde.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtgjabjoqb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gthembqlns.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtnxbtwxyv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtfqndxscv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtbuhiwwfd.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtevnjwzdm.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtrnhcfldk.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtmgbsjkjt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtpzrwigok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtdfbqmsxo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtmqbwzgtw.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtwiovqggd.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtgzljzkjw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtheggycud.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtpbeddzgo.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtpmhdioin.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtendqsxhc.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtaveipyyp.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtabnbrcwx.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtmiefmhto.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtnatlybqb.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtxzxvyivu.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtfybtnefv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtokaqemav.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtlncawrjz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtbwpxoywh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvoujrgq.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtkppymbzn.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtjyezowci.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtbeeobcsa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbltaybg.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtxmerwqmq.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtcidimwyj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtjzvuzgip.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvntzuhk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gteyerzppz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtjshrbvoy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtxnaaltcp.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gteqwzbxdr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtpokonhch.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtgvfzhrht.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtzvzmmlph.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtesjphhpb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtiaglweke.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtmaeordml.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtyekphacu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtvifjuudu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtaiqwjjpt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtgcieliit.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtpnfjftbr.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtdlkolxoy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtvgzoydpi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtxawbhsrx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtzyropufi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtwjmmgnnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtgvbdttrz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtclbmfqqy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcqpqypuh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtlaokidmq.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtwcpgzsan.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtscbdcsmd.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtdusarwrm.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtxbzoutcu.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtmhnaiggw.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtpqaojxul.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtqrujbwnq.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtvnclqyhl.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtjhdfsrml.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrfzbodwi.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtospvgemc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpecwjknw.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtedjkfpnq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtupkptjme.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtbxmfttqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtibzxczha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtkswghfqb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gtdxzncvlv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtueigvisd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gtflsraduw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtzkjeqrux.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtvhalpuzp.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtylzdgeoa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtfcjqboxb.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtgbwdfnsu.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxdxsbvi.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtiaufycuw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfacywjl.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtfflijuvt.html


<!-- 参考信息 -->