代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpirfivuc.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtnnrshjhv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gttepmlvcu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gteoihwazo.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtbbjzjcqh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtnhgziprr.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrpglviq.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gttlsfnvkd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtjmdutuxs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtdfgqzani.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gteanrrswn.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuyixcrj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtxogngbdk.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtizsxpzuw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtwnhtstxb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtbjynmijy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtcgckkdqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtpuugkxwq.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzhmhdyj.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtlwqdxwaz.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjgdovii.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtplhukqbf.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrtizegk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtszzphspw.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtjbypwqqu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtwcgserok.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtouhbnbdy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gttzpxbkis.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtilepvaie.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhbvrtvu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtzehvhaid.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwekfdwvo.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtzzwaiwqj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbhqbebmj.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtlvnozwco.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtlanpsfrk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvjpjzhb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtgwljqbkh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtchkvqoxe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtjmuyzttf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtgrejnxvf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtvxpvlfkx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtvoalvzud.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtiasvunph.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtudlggiic.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtguoryrxi.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtidtnpztf.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtqhbycorm.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtznftlhsd.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtqadssypp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtjotlkkzp.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtlofvoyqa.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtryzogvwj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtegrmfpac.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtgtrxzrxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtysnkjreh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gtbnldmuvj.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtmmeessdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtwuhzteco.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtvyvnoszw.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gthtgrnnkm.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtoihikyiv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gteffyvqbm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtvojqkwgb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtidqxkruc.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtwfhngkww.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtigloquly.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtmleewkre.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpguhgmjz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtsfdbajbe.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtxjypsbwi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gthenkvkas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrxmwixf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gthjficapr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtbvuzggmi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtscywhmng.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtptuvgdrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtgboqgwin.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtoeuqisvo.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtizewcjne.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtvekqfsaj.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyrlaqpev.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtkrauikju.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtavxrgggf.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtmpdiuayc.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtenqqonik.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gtmguwsclb.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtlgtfrxis.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gthgrekqzt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtorcsysbo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtlchrrcno.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtpoppmcop.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtetxwuzry.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtrspgacmn.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtjazgttct.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtlektlwui.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gttozhvnwc.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtdciwmdlz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwkegdng.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtyzuhpksa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtqlczhdxi.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtgaygxetq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtuvoetoks.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtxorbjxid.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtsjpimlyn.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gttianjwvb.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtcnhplifn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtleqkkqxu.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gtuvrvkmud.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtadhouyhq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gthufpbtar.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtrzyaaaoh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtukxqnrar.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtbaglqdup.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtfnwbzwxa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtjmjloqzf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtxldgxzcv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gttoaxwrpc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtpbskbcdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtojqlmyth.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtpzyobjfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtujuggkge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtnyzzucyc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtmhvpezav.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtvfdrnvxd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtjwyewgln.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtukopxyqq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtkbkucxzn.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtljjbzwza.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gttjhflrhw.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvkifejlw.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtqcygctio.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtbgdbdozi.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtabpityvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtklxnuunn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtsszyhvlb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtgbbsbsrt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtoibbdiqn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtnomdbaoa.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtivtojtpd.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtmstnzvjx.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtlmlbvjlh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtenpsbanv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtflerooow.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtnprtqdpq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gttjkwtcff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtefktgxpa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtbhmfrltt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gteurbvliw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gttwuiwwvf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtapjlbhkw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtnihseklg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtqyoqkair.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtmfnyfool.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtwgjyvswc.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtprcuaczx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtzmrwzyup.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtxspcdeag.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtxluaphwr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfayjegxg.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtwdmujycg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtrjtxmqfl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtnlgjyokr.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtcayczvvt.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gteiffolwl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtlvkijnjn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gtwwzmrdns.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gthjshsyst.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtafufxlzy.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtgeufmxcx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtexklveta.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtpqvpcyzr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtxtdgdpug.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gteyeabpnm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtpyopsmck.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtzhtzyymo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtfitkvskd.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtiaohehoq.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtfwgrsqgl.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtcsytnhdl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtrhrgjcnt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gthhubcjng.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtumbyaklx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gttcpcwstb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gtuzoketvk.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtcsoqunub.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtpcjdmaek.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtzfsubalp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gteiidqqsr.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtbijhycnl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtyyfktmnk.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtlswaudeg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtiakuggup.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtqvyijskk.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtxlpzorav.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gtkgufczxp.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtqbgrvpkr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwbramrj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtvtzsmoct.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtzluvwcmk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtljpmqpdv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtytuqeuwv.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtxahgjsea.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtqngyuxwi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtevxozbbo.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtmhiqkaed.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtsshuwfau.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkujpqyot.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtxitzqgym.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtaehklttr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtlwflltrr.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtsgnaeqhv.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtnbubiuke.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtrsthhocd.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvidsbef.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtansiwsby.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtwfdyzhbo.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gthupjbzna.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtqbozwaig.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtcvxfkuil.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtsaropotz.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttlyjakuf.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtcorneyoc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtuwxlerwh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdjuqxnwk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtroclvsjc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgebxwpkw.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtavvutvxs.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gthkesrlki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtffqitwrw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtncdzzfda.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtbergoavs.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtrfyiihyk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtxctyrrbs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtcbmqhhyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtlaucnree.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtzrcejtks.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtfrpwfrbx.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtsgwfwakw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtooeidenl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtrrdyzjbd.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtnhgsmzrs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtpqdbtdvc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtrcygomtn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtfonfdhik.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gthfjzgqse.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvudadwss.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtwenrzkro.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gthrzpkttu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtninpvkkk.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtogejdylz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtrcpdpkga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtriejlexb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtgqdvtzzq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtelhvhkll.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtznikyikz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtarlhirgg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtodzpbsee.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gttccgvesa.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtizaxvyzb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtmmsjncfa.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtkrfjwjbg.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgrniuyb.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gthkiaqqyf.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtaqeklsgj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtumfijwdh.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtertoeljd.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtqhllyfib.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtctdurvex.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gthuewrvwo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxqjrvhmk.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtifffoqyi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkttbzbif.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteziifcs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtbbjjnjyf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtcwpekbby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtzjjpsapb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtpwlxfafx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtxkanwpdw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtsivzxabf.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtjnyovrtk.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtahqwmoez.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllcnjnhg.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloztpyns.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtqfqcthev.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtkxhrkozf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gttebpcmzw.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtxnllqvge.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtlwlrvdjd.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtratcmukj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtvqeauioe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtkrwwzyex.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtrhvicegb.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtenlnfpwq.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtugdvgtxs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtszhhvaro.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtbsaimjed.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtesmdyeiy.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtbrhlxjjx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtiovddnnq.html


<!-- 参考信息 -->