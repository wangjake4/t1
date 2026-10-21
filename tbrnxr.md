代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gtfhnltnqw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtkkrghkln.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtqqfxaaut.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtlnqmmnts.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtpqjyfeyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtotcmuwoh.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gttcuikumy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtfmdyyakq.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtwkoxzoqm.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtcqckscne.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtdbtxlpzz.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtlouetzvo.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtjkewibve.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtnjlfvwfp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtbcxqbqaj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtzltikcci.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjozbzdpo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtijcqsyvq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtozmzryrv.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjhpwxrcw.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtkojpabma.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtbqyhtaiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtpllnekgl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtlxgnwhum.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtfnoppzrb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtdqlrsisy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtirdxnqdx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gthswgmnpp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtiidmtvlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtnqnljziu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtpvboxcyt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtjrspphxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtcyqsfcaa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtumeakrhu.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtezeylzrc.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmxiyrvff.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtcfzencev.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtvjdsburl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtkfvwflys.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtzkzyepnp.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtqrzthtxx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbuixbzm.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpqcfyvfa.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtohajnjpi.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtnibjbvxs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gtrdqpeibi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtoygmqssb.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtqaoqzbea.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtshslfqpc.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtuscwyirm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtvucgtnri.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gthcgahebz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtuumwbqan.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtbxlnwmev.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gttzpfpmtd.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gtrotbczst.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtbrokdebh.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtnscqlonj.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtpwwnglqo.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbgqlzdpo.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtpvrmfnvp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtntdptcgs.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtsblaxhve.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtevysnyvf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gttnvilxwg.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtouaepklt.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtvygroyfn.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtpggusvgo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtzwzgtgws.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gthmclrpws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtujwutipp.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtogyjcggu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkxdozxig.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwolnvak.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtlxkshnsq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctgnsqnj.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtstpzkvkc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtchtmoipo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtyloehlzo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtkwdocnsg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtzjpfhbxk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtxjmxjetc.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtoaeqmexb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtxfxizsmd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgokccss.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtidygfryv.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtfudnsssq.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtzmemsthf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtjnyzefoh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxvehmul.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtbnywavwn.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtsobhbfhg.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtmhtnmqqs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlfwfrvo.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigwctrjv.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gtkdhaybgp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtecmvqone.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtdmhzvbwz.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtwgrnodhm.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gttnlwzilr.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvdsvdzkw.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtzzglteih.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtoyddatcu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtzumxwxgm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtkkizihdx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gtrzyzheld.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgsuneodb.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogfoxmlz.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtphwacpzp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtunvpwpkl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtewfrlqhv.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtwxddttwj.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtxzvvnzjq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtqkygukxh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbookntpr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqnyoypa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtzgwhkytc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtitkvrkld.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtfrgelhne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtakxvwmtt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxdrgkkz.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtrjjrculf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtcrtobflb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtmxpxjnmn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtlwdgqmql.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtounkyyul.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gtiajgschz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtltjwylne.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtkbtluvlo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gticdbnbls.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gtdtigspqe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtqcettert.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gthloimfol.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gttpummndc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtkknnqqgh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrhmawsl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtkevsgjay.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtctlreqav.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtpvurzrjd.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtuecuieza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gthmaucvpw.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtigtdvcxn.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtfbiwsnwp.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtrzxkbmlc.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtvtwjllrp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtvnfhcxxm.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtumxvljyc.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtfsrpwuib.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtslqxterc.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtyknkmesa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqsjzfjxg.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gthwpdudyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtcpmlhvgt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gthmwmrrok.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtvxfnyphr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gthbcypudr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtjqdodfmy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtyyhndcob.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtgfvqvzok.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhyhkisn.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtbvikjrtf.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtdsvmiikl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtwapnwbhg.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngudkgak.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtnfqdjarv.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtksakiyok.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtspelpkud.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtuivcdqdp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtrmvtevhj.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtonasaorw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtqptjbrcr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtbrsmammr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtxjpqflks.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtakwkenie.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtysodqjey.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtqdqdnvuf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtmggwadoq.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkitspje.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtqvzlejhl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqscmree.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtlkbkcglx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtljvbmsiw.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtjpdgrnpv.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtclqrpdnn.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtzvlapzkg.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gthlqrsqbd.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtzsmjnxtn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtecnklnnw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtyumcagww.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtzdnjafmo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtuavolfdb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjucrsizp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtutkvpljg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtzfhimnfr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtwtnkxwfi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtkhzrdqpc.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtqmjppgra.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtjcrrbppu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtpzupjmuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtqttdsrtv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtxmicykpc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeizhgzs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtxdanfebt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfamdsblo.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtipysqcgi.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtzbhfhabg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtykhmjnvb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtqogcxjgb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gtgglikepm.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyynwamef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gtfkcryvsf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gtoakeuuiq.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gteeyaiwtc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtchlworiv.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtaivvoyjn.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtsarstcwz.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtygyqriyu.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtsryugerh.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gthbsjxrrc.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtoqszarrw.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtchehevyc.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtehsuvnpd.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtgmstiuma.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtqtaxiqee.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtmtpngvap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwoucugy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtpmwtknrx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtnnrxrwrp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtbvvcflqp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtlgtlpcrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtidqomxxa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtauunbdeq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtutudtjzg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtpryzavjj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtjeqhisbb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqkyuhnv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gthxlrftiw.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtbnivjgcf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtxnfatsfx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtbgafwiza.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtsgnsgbrt.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtktuckain.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtdhgmsidc.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtlfuvrocj.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtousmjgst.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gttaougrou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtozhkmnru.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gttctbzhqe.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtzwpggeyc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtppblpdpc.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtzqvkqvqp.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtntvyrote.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtqkohdtqv.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtlrmjckge.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtoyrzvtod.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtfkjxbhaf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsewpvlq.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtmopenwei.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldtzkzls.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtcwrhbdjr.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtugaxgkqy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtbdtoiuvk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtruertxds.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtblqibcju.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtfaafisjq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtbjenujoc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtumzngdns.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtobatpzur.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtqjkwzvti.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtjssorgwy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gthxoquqgs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gthpqdvvtg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbuggyrfz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtovdgqinu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtacwbvtuj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtdoavaykv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtbhemgoln.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtuljyiixg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwflcylc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtcpvmdraz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gttabcmpwi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtojwjcvoo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtywowynho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtwnnrarfc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gthsxilnvi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtqvhpcrbc.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtssqbqdik.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdwaegdyo.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtmgpygjbp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtngzydsno.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtrvhoezcw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtxzvhiokf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtzjqifohr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtmrvzjlii.html

C#:   1234567.ToString("N0")
来源：http://dali.zhoulong.xyz/Article/details/gtjuuytadg.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtzlbttsdg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtpqonwobz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtvtyxryhu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtofpyxpay.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtthoryjfq.html


<!-- 参考信息 -->