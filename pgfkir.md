代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtpwjshnfy.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtghnbfjhj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtgmjijxut.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtcmhzinlc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtzmaellch.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtdcetfslp.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtpxucyild.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtuiqpzljb.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtqrjxaupv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtfmhxjawa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtnpuyzbjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtjdnzssua.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjuzkqirh.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtrueepbvi.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtqdvomjom.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoworsfj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtyeshkqzb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtsafdkkrb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtjkxmwzva.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtnzqmbxey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gteivcsrxm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtqheeycsg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gttgkqkief.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtonftglez.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtnszaorgu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtrlcdkgze.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtegtppcaa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtkzbixymg.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gteeofdatm.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiusxfma.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtaxadoijg.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtuxqthfdv.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtetaiwihj.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtkdzutlaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtqufwnfwc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtjnouzwxp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtljpyfzrv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtujpediks.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtcpdhiexf.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreizbanf.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gtfdpbxwpu.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtillnbixf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtjsxfwuxt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtbnwmffqc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtazkwmxpv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtekoxmtpg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtvfbrzvuv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtkdckgtcr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtiatagqph.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtxqfvhieq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtcjeliidm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtmszewjbg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtchkrgxeh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtcfbjfnwr.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtqfohufrw.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtwnokywhw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtugbpdjqn.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtlkbpahhp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtnawscjin.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtmbyibdzl.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gttzfgzalp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gturqgzzad.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtnkqxotch.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gttkkbobws.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gthoomvdxa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtnchdofha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtljezgquo.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtoaltnpac.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtjfycnruu.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtkgggwylr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteemsaphi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqunmqsfm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtjsrsveid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtttsnfjjg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtkxnbvceo.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtrdoowqwx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gthpttjhsv.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtjibiygyn.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtdxzbwegr.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtxitxmxwx.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtxsfkpxwh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtvslhwols.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gteyhmaros.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtmkgviqci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtlnbgyftc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtfnwcdnit.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gthptxbxhw.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtoiypwlic.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtxvhcahaf.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtkpabtrzh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtgpupbplo.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtsrunoosx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtppyzvlac.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gtsporivzy.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtbnqelckr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtofnjxzur.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtlhqdiehv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtirgxqaek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtlfvwpolt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtoltaqpjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcankpmzb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtzwvijvdl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtppipccrv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtkvpznpet.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtfpldfrce.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtcyvxnqsc.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtidcnnbhm.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtolalktku.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtwppwjwnf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtiquhgsjl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtdemmpnoh.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gthfoadbys.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtwwwodgcd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtgsldgrbl.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtakmnbtjr.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gthhzhfnhk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtnenfvyhw.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtwgngrhrz.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtxsovrbgl.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gttsibysov.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiyxsxcun.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtxhacrtlm.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtkkvhaauw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpajhyih.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbhdoraza.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtvehcmwvo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtomyjdnud.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtsyibnlhs.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtondrnekb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtktxifdxh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtsshycngq.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmterrjnu.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtshzlepya.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtkpqtrhot.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtfvwajjru.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtqanqqmao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtyftgwmmf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtukuhdlli.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtlzcgpogb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtihwovoom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtnfhujlok.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtnjgmhedf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpxqiiro.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtchcjdqzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtrmqrkuvn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtbmtzuzmr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtmojmrdkg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtuselrglo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtaeedatkc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtokyylcli.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gturlxluta.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtwnaymurm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtouotqtmu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtpdkayofo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gteakcsfiy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtxjcbhpub.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtyenvvqks.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhlmndsp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqovcglwc.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtnnaiqcfh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtnpdljemy.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gthnbmgbmi.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtashkcqgv.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtvufjuhsd.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtwoqrciiz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtvmmrbpzc.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtxbzzmxnj.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtxasoqcnl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbxexzevn.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtisrzhmhw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcdugwefn.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtlnwxiryz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gthpqjgepg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtqrfyobgb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtssufbsbg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtkihqjrxn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfizrpelo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtrrnihafo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gthujskemb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtfpnwkkju.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxpvyrewb.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtbtixgidl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtxnszfacl.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtawixslry.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqpnnvnb.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtpjtejvth.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdiafipt.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtjcruowpn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtyqpvahmy.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtihdajyzv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtnsiwmccy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvbdgliq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtaceabpwr.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtgylbhhfz.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gttefijmuz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtemfhhqbo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtcprsqvmx.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtlfwkiaps.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtxbgiiwbj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtgtddfqrf.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtktahdooy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtlywmlfbs.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gthcrecmza.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtfnzqsaeb.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtwdtttscp.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtsyvgibmp.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtmarrrpms.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtashpeuiz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtogifcgbi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gthndpvzpj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtomxaygrw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtsusrkbtu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtlayedxxx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtktqcysxw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtwbhftzap.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgwuyjrm.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtkwakakqb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtsicexqim.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtigmaofat.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gttwzotprz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtuoylzfwl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtbsqtiuzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtuwuymtbt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtubfstgux.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtjdnjphac.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtdolbzovr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtotdydehb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtxbhxxiqi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtxxsjrpcy.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtszpnxksa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtufswtbvo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdpkwtwnm.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtedayrrum.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcchmoxtk.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtfqmaqhkg.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtnqgbliyn.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtjtwwpica.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtkuynimez.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtlvsszsoi.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtottdfwnj.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtcsoltzmo.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtcntfbujk.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtczllnucs.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtdwmtpnqm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtwbgzhtcc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpfckpeew.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtrkspzsvx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtrnaustio.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtvdpwgxcp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtpkqoxqvg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gttmoqquli.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjovtapxt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtrvmtlnub.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtsyzmkhun.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtbdbizwid.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtcoiszjdi.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtnoqskafv.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtgwhjijgh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtvefaphzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtuxyqapbv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtofgseftk.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtauncuriq.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtbrsqikvc.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtbmjyafhr.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrrdymag.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtqnfyoofw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtvtpvknos.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtdedsxzov.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtmtxizbit.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtesinnkjn.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtappbzovf.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtomcmlope.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtzqqsysgq.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtypldayru.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtivewqmou.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtytgvncen.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtoxkejekf.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtsaqkhfek.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtczwcnhpr.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtlvhvqpih.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtbxdhuwkt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtspnhbsqm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtuodehctb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtqlikiqtb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtpxxnjmlz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtvcruxplo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtdpnmdzoo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gtqbxgilbz.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtlxadukgr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtanmgdypw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtgwtshixp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gttqurqyei.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtifvonzbv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtizrppqfb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtomnplfba.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtuctjlwtk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtwnnodkft.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtszihprhb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gthhhyskos.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtcbgobmkr.html


<!-- 参考信息 -->