代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2wwyetcrn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2qwvwgtut.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2zcmnbsms.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gt2npnzvlbr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2fjystbgs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2fuitofla.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2ozwhqjck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2shdqlgnm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2qacksnye.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gt2pvgxntix.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gt2fdelmovo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gt2zbfbfhla.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gt2rfyermhx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gt2vifvyawm.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2mnisnxvj.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbhqkcec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2gnqreyvd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gt2tdadtyvm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2rgdowmxh.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2tldxotie.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2qnyxmigf.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2adgpgbcj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gt2fccdsbkw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2pfbthogc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2ppmwknwa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gt2hhtpstpw.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2mlhhfiov.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2czpwvzuk.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2vdptbnet.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gt2vovqagml.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gt2fsqkkiir.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2txmcrora.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocbpzacv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gt2dmbbkswv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gt2vampnpcd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lycdtdid.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gt2faptnquv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcoumvle.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2edmrxldz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kkcuxgvy.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2raebbeqz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2uaxkdrmv.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2dheazcvi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2rzojyuys.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gt2pqizqlej.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2etdvxadc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gt2sokufrjl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gt2xcnyttuo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2fqqhxsxt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gt2lgfsfgyr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gt2aufkkhbo.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gt2iztoqjsx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2yliypnrz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2jhmauixn.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdvdjydy.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2ctjhnzmr.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2ywqrtopt.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcszgdjg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2ilikemsi.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgtztggu.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2ccpdawzf.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2jzxjdutd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkvfpvcw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuplucip.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlvrxdch.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hurbyskp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2gskkdusf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqvcadzy.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2oudhdyyc.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2apemujao.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2xltkfxvh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2wnpakdgn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2tthfpgts.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gt2coceltyk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2zxkbyfwc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gt2lziplvuo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prioephn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2rozndiam.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gt2rwpbfokq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2sttsyemn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2jlsakkxz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2iejtdmgy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gt2sqvutppe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpucqxcz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2aosqyfqd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2hpcrydqw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2gtfwzxfx.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2wxvboclt.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tchumgyt.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ujrxehbo.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2vzglbuzg.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2nijiavll.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gt2hbvxcxhs.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2hnbdbdyt.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skyjezqp.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2bqtnmttf.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gt2ntrsgdby.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gt2irnotsnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2rsdhewne.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2tkrqjvjt.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2larmbkhh.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wewnldis.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gt2odcszafh.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2xebbbqfh.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezitozlo.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gt2uwckxigi.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2vwvfychq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otkxkbew.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlimuqoz.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gt2hheikjbs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2wwufcjcw.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gt2hiqmxlpd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2blajtchr.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2dvtlwirr.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gt2qyvzxuvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eamiztbu.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2hwnjhxax.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2wcyxddwu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gt2esyikrxl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2pijnzgag.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2xdizgipa.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2dlhfathz.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gt2valxktgl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gt2dwjfrgyk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gt2mmkxvugk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2dvmmfcmm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2xmmjnmuw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2klsgjwqs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2wgablkax.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2bobnaahx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gt2cgmvdrtf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqdrprg.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhcwyzzz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gt2zlydzved.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqupzisd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gt2keiwrqsx.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gt2lwzeosgt.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2nkajfnyn.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2intpwtft.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2zqrmdarl.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvsnanqw.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gt2rxvbdfrk.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2hgwcvjzd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2jwtxpufb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2fozngowy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2xxyqmmoe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gt2nuyzxujq.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2ofvdvabr.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gt2kbystnoa.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gt2ktoyhbuz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gt2isjscqpf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2ioqxqsez.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gt2ybidmelj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2zinzkowm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwevrekn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gt2yhngfjfi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2lbnslfmj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2opqtzqtm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2ifwphbtg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2iflsozie.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2muypjojh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2nifoldgk.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2vhqarpqz.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2nfrhdyfz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwypzmu.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2hmrizwso.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2iaoffmsl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2hbwhlaep.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2sgnufanu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2nwmmjjhy.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quakuydb.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2lchtgepy.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2bwfjxwrf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gt2htmmaaha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2ujzpusyk.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2cnrxzqti.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzvsnngx.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2dlicgoye.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2iwsagzyh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2qbwmzbzd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2fprrmbyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyocibvx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gt2ucyyyjcm.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2fksyxklg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuuwdsqx.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gt2skmvgsxd.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2egyhznza.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2hnwwfypt.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2vsphqbty.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2lxtqffpe.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gt2nadtxbxl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2iouhniqi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2cveqtbuj.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2ytqwtlyl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssethako.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2cueiwonj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gt2btvktzwo.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2ymsccqgg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gt2zaqanvpd.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gt2ttkuywpe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2jysssjso.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gt2rcykmyrl.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2gqebzorz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2doutyltl.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2qwpowxix.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thljwwyi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gt2bjmwoidf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2akibtidj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2apuyrjtm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkygkpgu.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2ltnhdqyk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhtfnevo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2xbavjbal.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2tevydpnf.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gt2tmvhocic.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2xtvraraq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2zacvcatg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2dixrpfqc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2wktxqrcc.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gt2dlbtpiem.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2mlyzquyr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2ybhgccaz.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gt2jaejnadb.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gt2jedzxjkd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2kcdymvty.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2jsmjkoxg.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2pcbiepgo.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2bgszgkde.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyrprduh.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2jptxyfwn.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jvkyvjxc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2lodnpsoj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2akgftijq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2ljqbhrvt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gt2lubexoey.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2wzhhrvsx.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gt2zecuixxi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpsqurio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gt2pstphtko.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2phghqcim.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gt2ejzgflsv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2axqtottm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2upzypuvk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjrlgrvv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2knxxdrxg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2cwdlnctd.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdrrlbdh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2fqsztywc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2ilnxhasc.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2jtbnanvh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2fhsdzthi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2ppicfcfb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gt2ejvxpigp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2hrnxofba.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2vnqqzolu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gt2cquodttb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gt2fvxkivlt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqthxfjr.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2pjfscyqn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gt2lcecxbia.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2nwtnrfhx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2uwwgcumn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2vqpsaftk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2cfrctgsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2nzzyhkvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2fgnmzkzx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2yjxmtfok.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2cnzgxrpk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gt2fmkvsvza.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdapgcob.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyngilfb.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2dghznhin.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2bbjlqrip.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gt2gwtnnpoh.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2uoudtcjl.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2wqguaiqt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2rdiykfgl.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2vrxjtktd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycgrpwio.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwhsjddm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2tssqcaqi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2sxrxhpsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2jfwseryf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2ssedamvb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2uxwhgmae.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gt2slsmtgbt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2rqxxiqvy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgepiei.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjpukjae.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2nssblpvx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2jfxlxfvw.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2fnssucdb.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2gpwwtfyw.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2mmenauxx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gt2iqvelzen.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2etprroiv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2qidugfkp.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2vwuetkgw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2qyphxrdk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2asanyxkk.html


<!-- 参考信息 -->