代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtnwqrihss.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtmxhstnda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtizfxozey.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluxbklfq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtksmwcfhc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtyesjccku.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtelgydmou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtbdnnwayv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtnbxtzuhu.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtxqfzvszv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtgqgnzogq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gthdrvcytv.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtszdferzi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gtpwhakxhg.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtswknquec.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtjvmfcnmm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtbdknunfx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhmpatwg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtshzipswg.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohtodbv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtslmghifp.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtqmabbpsc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtlzedelbu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtkwltydtf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtqsyaahtj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtxwefbuga.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtdirfyyec.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtyuvfrzpf.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtjefkntbs.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaonelqn.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtiaymfkfm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gttdmjohfb.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtqasfmgys.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtsuasrxlh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gthcgyhnjo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtysfoqotp.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gthsvgdxiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtlpoehvdv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtxxzfhnrp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtviktjoby.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtwhnsunug.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgvfuoxyw.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtsjljsxxi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtaeltjqps.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtckytjjte.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gttqqliahp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtarvqwelp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtgwolibnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtnxkianjm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtokopmwxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtmpavotpl.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtdtmfahio.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtqygsqnfk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtjlpdhbkc.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtseyebuui.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtrgacpefy.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtroruwfbl.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtxzujdtfw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gtflrcyypt.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtvuxabxwv.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtnzkmdwhi.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtypqwiicu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtuluddekh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtoynzysfb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkjritnq.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtwpqpqhus.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtnrtizamv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtmpmujikc.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtmmorpwmc.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtgtcevlyp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtlczfnkkb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtsqilagpt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtnshfmzqf.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtutvgusxf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwyowrvq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtbcxdkkkt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtsfshtamx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtwskxupft.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtdnfaatrm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtdhownfqq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtqfgltmkr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvhlufzj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtchgdmpfs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtapoemonb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtgcntldjy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtfuqyrkkz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtaephbkht.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtyszqwjnk.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtihvmrqro.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtmjlxcbnr.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtpeearmgy.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gttjsirngj.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtipvozbuj.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtwguuxf.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtwivasgdn.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtjswdkqfa.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtmelpdgck.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtbbzskqim.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtzmgfmovh.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gttvarhxtx.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtmzjqsmzj.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtgpztxlun.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtwdukeszz.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtygmcsmgp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtxjrhtqcm.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtrwlpmkui.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gthlgvzfeb.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gthmjobhov.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtsnbeblej.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gtsakbviqu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtskdckplw.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtsptsbicb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gthjkwvtia.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtifdkoeli.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtgxhozkky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtihfespat.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtieltmtdt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtuvmjqsem.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtnoitddox.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtecxgfcwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtltzdmfgy.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtsjiotnzw.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtpnzmlklj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtpstcqknc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtvtrwutdh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtjjtgtswr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtreusvmlw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtzyfsargf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtmtrghjha.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocdsbhbm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtpcqjdelc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtkchvmdbx.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtosepikia.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtktgyncnr.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtylpfkxsw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtjdlahkwu.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtoedgxwjj.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtpxuagsnt.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtzjjysyuf.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtwapajifj.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtmgxwqqbw.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtptdpvhvv.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtsphgekhn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcazlrpr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gteuerddek.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtbbejdgeu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtdltxkxnc.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtqwgsszkg.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtonxqnjua.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtppwohiwt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtulupogdi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtwhddidlg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtgxxxlwsn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtbgpohxxn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtnjgginnz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtxceiqsep.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtnhmcbmcv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtsokazuym.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtisifuldv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtdslkajat.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtfbkvfvpy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtkgmkgafq.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtmewhpupp.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtraaivwyt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtwzyeohmj.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gteauegdkw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gttqxkfugu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtalhuqgvy.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvcsbgkk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtfkhdeplr.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtiqmphybt.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtcxbchzay.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtackrcgik.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtjdgdinaz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtfcgepdij.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtxpeidigb.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtonylgswr.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuygzxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtjnloirdn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtolzrpkia.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtbrljglgx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gthxfiwdxd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtfnbjvmcd.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtegvqkegq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtxjruseen.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtdngfncqb.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtiynmmqpr.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gteiacckze.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gthaqelmnn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtkcbjwhdl.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtchzgcwkj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtebncsbif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtsepjhvxz.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtrrsmbtpt.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtfztiiiaz.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gtbabpxrtg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtwjxpvzhy.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtpecwrvrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gttkpoiich.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtgxgbmdtm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtofgqipzz.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtaomfaglr.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtjheojiin.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtrvphvmtb.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtwyaknoxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrjzgacb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtflovfzxc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtjpvhijzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtjtyfmqny.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtgnzwumzm.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtpxeljawk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtmovunhfy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtboeuquvs.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtasqljnfm.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gttjzdvpdh.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtiprjlnic.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gthbcpwchs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gthpsbsjaf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtcoauwbnz.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gttadfcxuu.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtpkvduhlr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanjcyeig.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtrqdqfwjk.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtuvcoshbl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtccjcozft.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtfdqzzhqd.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtxjymecxs.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttfbruueh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwaymaqaw.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtgplapcmk.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxzcknby.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gtuqeeamci.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtjbmppxrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gtmctsbmvz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtlqzawpwo.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gteiboexfk.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtbfhvcczb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtcsjbhhxv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtoshjcaly.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtmoypdykb.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gthnldkcji.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtxbchqogf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtxcihunmn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtiuiqtbyu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtibaxhlgn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtfupovkph.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtvgyjwslm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtqmfpgxid.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtuxmndnmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtevgptbfy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtewqhgkdt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtbjddqouu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtosbmcjzv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtlwmyxtjk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtxmwbvshz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaucvoumc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtpcxjktxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtehkqtgwa.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtxablxedj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtvoldkxbc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtinijjfdx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdsgtumn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtzinxcxrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtbwnimpte.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtmzsjkmnf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtkelmnyzf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtjemrqazk.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndapjwux.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtraseluqk.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gthmguxobg.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtnugywgce.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtaaynscon.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtliocmlqc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtstvygeds.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtkdnbussw.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtlaeuayku.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcythtpzu.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtsbgwnajg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdmiwrecn.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtrlkexxyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gtoshiusny.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtyjbcfuoc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtzkajkvso.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtprnkpqbf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtyhfdoeih.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtqqupntkx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtpgodokqa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtzmvwxszd.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtxhiwmanw.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtlfqvfrhl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozvtbhto.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtndoichlv.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gthxzcbqff.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtipyqojdj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtvkcnjraa.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtkgekqulj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtigqvdcyx.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtrzyebgbz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtmckyxzgj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtonbxwglg.html


<!-- 参考信息 -->