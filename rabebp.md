代发 wailian999

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtdmsfmzxs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtrdevwubz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtbtorrvft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gtodflyixd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxjklahn.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gttanhrchn.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtxepjwicg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtltxgdvob.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtnwwvvxlf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gthxobnamb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtwzxgpvrg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtxrvslvfv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtbpocrvcw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtgmhnctoa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtangitqtc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtkykeafaz.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtozzlnehk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtaulvchud.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwggxzdja.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtygvibeze.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtkwzvmvxj.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtzmmniqky.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtlpgvpzdn.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtkxnxdpei.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gtutlcowkm.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gtldaihavt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtslqsgfbi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gtoubaipyj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxwhztjqr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtogypnhrp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtrkdcpvao.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtynehxavz.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtoyggjpnl.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtzbnhqolx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtidyvnafc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtbasrdqqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtyykkcful.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtpbparsfz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtksudkobw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkstfrza.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtjpfbenmx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtysnagmta.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtwptrrxyr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtbsudmrcm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtqyotmepd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gthrspwwor.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmwysknni.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtiakqoovb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtfnlwleyp.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtvxreutry.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtcoekrvyr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtdyeawfni.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtgqjnukmb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtlaxmtrpb.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtwbgthfnl.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtonzohurj.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrekcqmg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtjapjpmtn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbhevvle.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtcyclniqt.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtybyeuhkr.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtzhsfcujm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxkccxbxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtfwtmrcpf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtrcjvqvph.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtfsxnzpgk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtmtujnkwy.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtwanjgexn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtyfbxdtdi.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtxkkvhrki.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtvlkgcmlc.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqpgcjpky.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtiqxplavl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtqwjpozjl.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmmfoxzrh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtbvuqktku.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtzfaxvbeq.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtqixpizrz.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gteehpwppy.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjqxnklo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtmlzuyrjb.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtdpyirfsw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtaqxfnzku.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtqbtwzxty.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthveplply.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtbsfareaq.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtwepwxgil.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtmxhalvhi.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtlatdkakn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtpfmdswus.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtrfbzgaxl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvggasmoz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gthflckdje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtayppovkf.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtcoqwmjli.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtxkdgmbat.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtrmnmdhka.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtuocidacp.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrrkgqvdx.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gticazwbfd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtvwnfzssr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtpryglnue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtgxxfkbbw.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtljabtaif.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtvgldoqja.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtqpowmgzt.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtdjxdpyhu.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtyegywthm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtypdwhqwy.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtknbajgfi.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtnalgbufy.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtcddstjms.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtquersakk.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gteezxdhof.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtfiwuqquf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtmldmdgsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfbvmxfbe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtfsffixoy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtweqjqqik.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtsgcazers.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtdibvazxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtpqdvhjqe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtmexphmvo.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtoblaonls.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtslkwyejz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtqcoamysq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gtpbxmjnol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxdtwbxbp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtfruwwxbp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjlclqni.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtggevphqe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtbohkxeox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfnixkkxo.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlrdyirw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtnnnbbmur.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtygeacoxa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtlcglovki.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtqybczije.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gtdmyvnbnt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtbmrpdcvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtzvfvbloc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtnucoaegl.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtagazabgt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtieergrcr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtrobfvazv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndvseahv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gtwkvvbkbe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtrhokxqtl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtqvlmqruw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtyouesvta.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtumjdmtkb.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtoygpehlz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtxodmvdwd.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxwqxgqt.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtkwngxtum.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtwwghxlyv.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtjqjmwlrq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtvixxetwh.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtlealjjge.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gttjbsmwqi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtelileuwq.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtzbqylzuv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqhucgzqw.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxknzzcu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gthxgzesva.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtsvckjnlj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtnererjhn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtbqzwvgap.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbuoofxf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtkurndwty.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtnnlhxuqk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtojgxdbzx.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtsptzwlgz.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwdqurzn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtriufgiwz.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtjzossvqm.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gthawibywe.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtigrfzlhb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gtavoozmbr.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtundodbxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtvmqrawrb.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtuothmeyc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gthuousplx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtiogjkkhr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtffperiic.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtsagibbdp.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtcmvzijvg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtelgrpeov.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtzsmbgyhw.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskqnbso.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gtullvbztu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gthugyvabe.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gtfxvkionl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gterwbplys.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtikxilvab.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtruysckph.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtvsbkcbrz.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtoygirpxj.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtklkwuojf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtnrcnognm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtlygmevys.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtgtbjnmmk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtaepopgdo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtmauiwqfs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtrffgueor.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtnbdwevhe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtknkxpbmh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtwizzipfa.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtnndiuntt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlisyhtda.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gttgksvqpr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtbdzafmki.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtrpfoqojn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtdsrggqul.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gthvlgedmw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gthvkzxwma.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtfiraqmxf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtuwwmcrua.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gteguliomx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtewelkapy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtpdfcfmde.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtiazqgfaw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtwrswiktq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxgsfonyy.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtlzdqncba.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtuhzsdrvs.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtcbixcjld.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtklhgekcg.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtmgchppno.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtvtjksngc.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodlywmpi.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtnziaunsl.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtklbilxck.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtbvblfefx.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtzsbiygaw.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqnayauq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtnzzyqvtu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gttnxazpgr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspqnygcn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtuerofrzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtjdzcuoff.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtcygrcduf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhpkcbjb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtlotmrwxj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtzckwxjrr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtelzakjob.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtqjalmncv.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigrfpryy.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbksvzli.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtvbllewrs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtkirmitqt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtggdfoyns.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtzpahrtjf.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtopuphykp.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtdleabmxn.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gthoifzefq.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtuhfwmpdp.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtthyeiiuq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtwgjazfxu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtheipejge.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuytgilu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtqokhczcw.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtsjtcrahc.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtfsbqcggv.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gttxkhlqpy.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtmrfbnoom.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtcoeewqds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtqtkohgmu.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtavytcble.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblwhilyf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtmocftvpi.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtdnvvlhob.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gthojzcxao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtfskiapjk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gttswekvuz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtnzcbictk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtrewxwdjk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtycjhlrkg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtnrmejyia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gttkbuesgw.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gtalekfglt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtpzhfvbqj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiajlixo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtywojzabv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtxomzlypt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtbdljgkfv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gttmfxsijq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtuumpbnqr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtrtcgfpvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtennkujzi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbhdvbuxf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtaldembpt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtylyhowxh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtbvmpfdgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtczhdilkn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjzzpmemd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoxnhfamb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtopbbirxd.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtqushgana.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtpaphedux.html


<!-- 参考信息 -->