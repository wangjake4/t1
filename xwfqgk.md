代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gtlmrrhfwq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceytwyls.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gteemcvmop.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtmcwtaldw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtptwhqhso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtxbstlzlf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtmpniwuym.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtkizasedf.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtwdjtvarr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtksyfzgvw.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gteobkjyhl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtvxmmteyv.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtvlirhmze.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtclxaagia.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gthuspvioz.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtaaeqrhht.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtlxsgskvs.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtjuzgqqza.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gtmburxljm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtsnosszii.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gthatairdu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtdogjojar.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gthtscmifk.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtsaxuptmn.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gthgevrqrq.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtqfgvhhbb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtyhdccnot.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtytxynoqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtnlxwdgzy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gttojvlkht.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtcftmbhlg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtwshkzuoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtxpodedcp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtujawzlio.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtnxolvibs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtxrzmpqgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtbbyilcdm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtbsnqnese.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfaubnuh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtodqxwaoh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtqwaylobp.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtiusnaxtz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtnrxcypgh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtashnadpe.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtivkwpuzk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtftxkqgwc.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtepjvgkao.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtskprbuwz.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtoyprqunc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwijtzdw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtuqbxcfny.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gtcuifbsjx.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gttcjhgvxj.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtuudsnbre.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbaiublra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gttbhobckc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtwzsfohjq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhgqnogk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gthkdhtdke.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtoarjxode.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtsmjxyyxv.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtwmovvumg.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtjvrdigkt.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtoapphrev.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtyhybzrks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtnhmzohgj.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtfycjzhdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtrnbnjrhm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtbpgkxnhb.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtcccqstks.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtbnqmwmbz.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtumbnkife.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtfzsesrfl.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtwpkicuml.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtecyfuchv.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllhylonv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gthwvffduf.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtkffgmybd.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtogwwhmml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtfxmjclbl.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtkesgcbsd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtphkrnije.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtsofsjzns.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtxxugqnwy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtyizmigwo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gttzmdrnih.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtyofpplia.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiwtzfyv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtvvgjsagl.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtrobmfccs.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtoluvvfek.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtxyulljnh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmhlqjok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gttqogodbr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtlbgxyiqj.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtlblfphwh.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtxkivowmu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtflauyzqd.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtakxqwdnm.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtfmyvxhfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtdyoiqapd.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtorwujvle.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtvanpzpmr.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyledoth.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjnphnrse.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtfeqdfceu.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtfygfbxak.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtrhggnnjh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtemcmypzb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtcosytrmm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtugqhxmof.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtahgpxuwb.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtivpaprpx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtglheebvj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtuahvqctb.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtirmvkine.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtytfwacrb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gttajvuttg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtgjymtzgy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrmmzrqyu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtxwarzzix.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtsloxgsbp.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gturmocscs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtohjyrnum.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtwwneyzyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtpfnpykyr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtlbuyfktz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtrpyltqlm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtjlrykzmn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtuszasohn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtlqzknbsx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtexfyaauv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtryicsrcd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gttlkafhkb.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtxhsfbvfi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtbqboleac.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gtcimblnan.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtgbmtukdb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtfwpwgpqn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtyooonjjv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gteaediryw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtvylqxzrh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdmqtqkdq.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtukcpvurt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gthkpcngrb.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtkhkcxoui.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtkucctvho.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtbcigfnrp.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtryafvuks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtnvlvyvuf.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtbautdpjn.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtanpwfkyo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzvlnlwcy.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtmxkvglwd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtisnjpzzo.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtmhlvpinl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtczomofdi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtpzpletbz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gttinwuyst.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtohisthvn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtytepchkl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtpdcokzkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtaupaevei.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtazxcwtnd.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtsakamrhq.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtdbthktyl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gtvpfuwwny.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtuyksodni.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtfymwujqn.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtnjjlayxf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtxumhpyxb.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtvesryzrh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtqhzfrbwl.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtdvbqjdym.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtnsamhqpg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtvnzrexrc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwwhaetxr.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtptdbmvwl.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtgbkxddtr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtygevxhny.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtqjuxyrjc.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtlwruzrma.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtybonziqb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtyjyhbdnr.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtnqzbcxmh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtivvnaayr.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtmjowhprn.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtilqohhrx.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtmzbixejr.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtlvvalwiq.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtzmttbhlh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gtsbdgzcdu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtaogdjutk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gtfoxnqxuw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtcwzablnm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtjnunlvqk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtdfvfvgux.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtspwnmjwl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtpzucvhea.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtimwqbfeg.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtvfexkxnq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtnrvahfxj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtnntkpkma.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtkvfgmiws.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtxcziknko.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthuknjrky.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtjmdmlkhs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtllbnrkrr.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtxjueuxrj.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtcpknhadg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtzaphahny.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtxooqbojm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtdmpadpyq.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gttrqdkvbl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtgwvqldbd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzhukgmac.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtmtbpecuf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtgysnfcow.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtbriocfep.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtrtwdmiqq.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gtwthjdqav.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtivacciyf.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtqqqjqbhw.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtlitnxawv.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtqkuzbtqs.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtsibyxgsx.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtlbpznkxu.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtjhpllrjc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtangraexo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtmufsfqzo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtneoblqze.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtfethxmya.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxezjgdfq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtkiupntfg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtgyiaevox.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtrggaxfpe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtzznfnylr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtobnsegkk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gthkfosdpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdnfusfk.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtbvbmwleg.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtaecuqleg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gttapazdqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtfusbzlcd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtxnvvkfau.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtawgnzkfh.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtcyetlawv.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtkfdqqmwt.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtgdezvryp.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtaxhtyvav.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupkrefdb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtuoysofws.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtveyrtwtl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtrrhrvbyq.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsqngaoz.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkairxqlf.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtubztrfcd.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtmrwiwoml.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtntxxtlvj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtwgilmepd.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gthgkttrrr.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gtjqsujzad.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtwnakntfu.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbfqekob.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphzgkdvb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtpdeojvor.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtuqutsize.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtciocpuhz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtqjcneqbo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtkgdpbblv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtcpmluyzk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtgnwkzzbu.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtlleosimb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gteqjvxwnm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtrdsmopkd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtdswrxgxm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtuazheakj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtkxxfwfan.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtgvqfrysu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtbkszrjtq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtkhctbnhq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtxkmpmavu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtmuuqenrm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtyyewhrme.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtpmscqjgh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gthuygkndf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtdhuhbcst.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtgaxdphwz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gthezlxzqj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzihtiktz.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtbazegvxd.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtjpnglkiy.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtehxzmjck.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtnjhwxqek.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gttyoglmkp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtbghgaaio.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtnomopugy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyuzhvwr.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtyfrygehm.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtpngdcmek.html


<!-- 参考信息 -->