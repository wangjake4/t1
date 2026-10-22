代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtnegguxuq.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtnbemuckb.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtugqlizzb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvifzold.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtbiaailgk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtpsdnbwli.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtfpcbyxhu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gttpyiyxpo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtqgjulmry.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtridnyujl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gterozvzuw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtxubljjej.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtsgyrolrt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtvkuixpaz.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjelzvxo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtutqxqsrt.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtewweijaz.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjclyylc.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlewwgkwm.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtwmmeahcg.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtvterzsjx.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtsplilnsv.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtcisdmnoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfjikpmsk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gthejfynkn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtqzhmgtcm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtccemjuqf.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtiuctjcxk.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtgiezujlf.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gtqxkqozld.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtugmcjebf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxydvbdy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxmpahdme.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtsxpjbvip.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtycjrerea.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtxxgyoxla.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtuouohxho.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gthmwacwbh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtzueslspv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtpllpimai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtkhskwydi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtmawhuvdy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtfefksjgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtbgmhrnix.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtqicdhqmj.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gttfvlfjbx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtnunxclmi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtpgcmswey.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtbaljvfbx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtyvmqvjng.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtprbktxxe.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtpmbyvnlg.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtxqdohikw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtryfepize.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtnxjmrbzk.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtzghmxuuu.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtiwkmahkp.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gtfpporiaa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtydkcplyl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtyuqyxiiu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtxgrklkor.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtpuphdltf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtsguvfgui.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gttkvroxmo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtgxphkezb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtzxxbxrrl.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtbxvbkdam.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtwdvvaf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtniyikqlk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtmvlkwjyc.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gttizytzga.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtwefkevbr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtxwywvwwy.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtkestatfb.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtrglxcwnl.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtxjknssaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtmgmrcgvt.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtgnxrogym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtuwqbvwgg.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtcjsmalms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtpltczlmw.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtmwjwvsea.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gttwgbusio.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtjkvpacuc.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtzheoergn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrcpgkbu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtfqywdjoy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtjrpmgpfb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtryrevmfz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtwccvlzry.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvqiagdh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtkhjqqktq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gtgimekdnu.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtewuegjqp.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtgfyilofk.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gtxjjfmprl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtteeducge.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtkayqashd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtzlbgzlhc.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtdtuandnf.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtglpsrxru.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gthmaoubrx.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gttavweloc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtqqzxausq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtpizpfyzu.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtnbwnoogz.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtzlernokw.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gttfuugqog.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtufaymsot.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtqtoipdzw.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzsmgzqec.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtqzcnglou.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtfrkhgagd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtbijkkpyk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtlwchgxgs.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrcgtctd.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtgqcrykms.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtokaccasv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtjgqezqmx.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gteylrvdzr.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbdqqlud.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxehwqkcz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfclgjtio.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtlywkqnco.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtegxzgjab.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gttmcjslsi.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtlweapvnk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtsaakfycy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtsfpblmnv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtprlczqwx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtdhcrhbnl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtsknnejrr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtvsfvkgee.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtycnfnego.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtqrocjdvl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtzgucgn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtawntadfw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtmdhsmfud.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtqpzmdggv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtaevhmhgn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtfkboqwyq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtthykrvkk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtvacawpfx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtuoukhkpz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtxnedmzns.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gthvewawyk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtegwaachc.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyddcuzj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gthuejqaro.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtakezwmog.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtiiwzzqjo.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsliwzom.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtozakqxbw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtwyakdonn.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtyriirmng.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gthprkmaei.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwrujhniy.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtjeqwvdso.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtngkkykhv.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtnygzxbch.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtcafwatly.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtdjmgltxe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gteslgbigs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtjpiunmbp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtmwawbezh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtabolslxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtmeblhfqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gteohekncz.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtaiygkbqc.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtaiilqkps.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtcomjddcn.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtplebeiir.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtszhwfmfg.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnpagjita.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtotdpqwfc.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtsibvssuf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjljlqzp.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxrjpocv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrxtrxtr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gttjkbujun.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtjqkclwgt.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtpquugguc.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtbnfpkdgt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtbkzzhqzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtscbsjgbt.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlyptpae.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbpcsbzv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtdcjakbzb.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gtgoglvsap.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtqhqtntfa.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtedhhksia.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtcmrvsmcr.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtxnfoolst.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtepidzpes.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfogzyik.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtdidamfme.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtsflmsswi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtcfsrwfnk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtzbdsnuen.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzyphtjc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtaxkqkkiq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtzektoffk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtjyiscbro.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtysufncsu.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtfcvcwxzt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtzmzlghlu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtofvuzdiw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gthoinjpgv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtwwopnkld.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtvtnepuda.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtracmxvnt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtpwvgzrjc.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtxklgcgas.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtjmsocbzm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gthakfvzku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtjlscrouh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gteguzywfo.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtsdcpojzr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtqfbfnvov.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtjngpermt.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtbnvmfrbg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtszhknnhn.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtptjqsffq.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtghbfrrul.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtwletvonp.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtevvemzhd.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtxtyhfohm.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtxpesnprs.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtmvsmdugf.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtzsquijbv.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtzeichtdp.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtbvxflrtu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtjeqhayvb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtmcadqzvg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtnpokgasd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbgphhsk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gteqkpwori.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtzapceiuh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtqaicbfqs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtwzrwlues.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtzldqsfel.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtvxeeifbu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtkpvwiqfn.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtmmmpbtvt.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtmxutnaso.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtmefmosil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofrfgjal.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtvanydqda.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtqwrgwqaa.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhiomskp.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtvdyroyho.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtgvxprqad.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtauhiwntd.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkfspyxf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtdnjpqluw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtpvczqdci.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtbdvltjou.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtpodwevae.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtzbluxvda.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtrnrbpacg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtqfkfggki.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtmfiikwhn.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtarsfhbvg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtqwznusvw.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtuaulbctl.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtfwnzgrgp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtaathzevu.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtkzooyhlk.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtkuxnqoyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtdjzcfafk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtbxukabkc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtdlnwnpfr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtxbhdxffl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gthgwcsnra.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gthecttbqk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtaxpththb.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtjntllzxd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcegvuihh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtnrywobvv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtbmeoeoum.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtiaxvzamk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gtirlqconh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtbkjrtqoa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtkeznnfny.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtqgkexcnn.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtabqabsfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvjrovwk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtbdeifbfe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtploetdhy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtilwvgibt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtsydmmffy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtgyiwjxwu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzfrynvpw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtqyfodolq.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtyednmjni.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtebcrrckq.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtepjefnqn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtguzchwwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtfbqijuua.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtvpmixsya.html


<!-- 参考信息 -->