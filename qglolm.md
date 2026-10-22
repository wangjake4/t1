代发 wailian999

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtssbouiqh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtnzelaack.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtvhwerquq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtotvhdomg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvycrblbl.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjnttmwwm.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtwnwiroaw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtzdmadvkj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtaluqnkvz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaleomwme.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtrhrzodnm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtlroetnab.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtafylapbt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtafextpww.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtedamkzor.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtrtmylnxy.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtgtvyiaxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtxkrjfzqw.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtdclrabls.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtmcyozwib.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtxfuoljir.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtmvdgvxal.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtsgkmyjuy.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtakpihfjz.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gtxzytrrca.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtprinjlyl.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtvbsaheqg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtvmbcflse.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkjaetcc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwhpupvt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtfnibjchw.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gttkepkkvo.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtuduhefky.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtlwdbyujh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtlbzsukwp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtxygdztaq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcvxbzje.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwrzqttd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtbggnzmvw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtvkbjmsxa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtrxubcfpp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtspcuiygi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtjqewiuvn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtdlewigoo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gtkjmzrtru.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtewflpduy.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtxwbnucfw.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtbhjekifv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoowoeblx.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtycwpsxkc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtnwgcvzgq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcofoajcn.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtttqcjxvk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtxpqffajz.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtlxfqinyt.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtrrajzfws.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtzfrrayvd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqasyacrp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtrocwfytn.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtbmtmqnid.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtumxylrqw.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtxarsujyi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtlfxqhisd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtjmtlixfx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuqrdztq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtfdiqllya.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtgkafeeob.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtudykynmt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtemrvpdtd.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtuqspifup.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtgtkfslce.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtlzwdihll.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfeowswzw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtxjpemutz.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyobdcolk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtmqdyzets.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxsubdnsu.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtmzwilvus.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtketnmbna.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtptvxyhtn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gthbfqcemv.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtzojuadwz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtsasstfmc.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtfghbzwoh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtpmsbzizb.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtbqthpkzv.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtzrclwqax.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gthyzhstmh.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtqjrfwbxt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhccltuv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtagrfaxwc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtvdozqjis.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtjpuziwal.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gttepfjaqr.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqczzqxe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtddteawtk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gtxrididhr.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtcexsryuy.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtcelvkuxo.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtfqbdzksr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtrykdjtry.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknbwzkfh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtlzmtrfea.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtadkzkfzc.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtygqjebif.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gteemcakkc.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gturrmqyzi.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gthcwzcnwc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtgiwndsgs.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtctfxilou.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtmcebsmkb.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtstphpoat.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbbmgedja.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtsemewkev.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtsjuakdos.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtlcfmzfgu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgmqwflat.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtilobhtmw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtspexpuiw.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtkxdzwuqj.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtkbmydrxq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtwgbpolho.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtgavuyyaw.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtuftqzdgz.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtmbwafbdj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtdcorozwp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtxgttubjm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtvihfnvny.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtuwnkymej.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gtlpslffvc.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gteauqurkx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtoxjrgjrf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtcliazoyi.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtiknyuhei.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtbrskwmli.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtkzqzlqhk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtcvktkhdv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtctyvltke.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtovwbnagl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtpicqpwrw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnirggvnk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtlzkkvwvb.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtcdbropdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtnfvexjcx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtzgjwwydd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtmxeqpovg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtfbqxiwjt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtpmslfxuw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcglyewc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtnnvuoyql.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtbucjhaiw.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtddotqyjh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtrgcachss.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtulsyopvy.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtflcjhvgr.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgkliqqi.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtrytcffmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtiotwhuhs.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtqsykwumh.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtbltjgyuw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgvynygjk.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gtbqkrauol.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdloyvmco.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtzinbnbhg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtcfczjsew.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtheatytze.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtsgocrjgl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtymopdeno.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgtzlhnz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtxmhpcpwv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtkuakdnyl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtobxddhjv.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtsqwdpsad.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtdynokftw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtigjrjqyj.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtysahmogl.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtkmcyfzno.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtgttamiac.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtdnadlqyb.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtqruronqx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtaceflwqi.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gttoziaqtj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtedutstgn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtshfrggti.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtfbrwwcyz.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtfvzynlty.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtteetmtlq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtkzpduzvq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtpzsxznlx.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtdyciezot.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtdhtdpojn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtcivgkgya.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gthkkardth.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gtuwmgeeqz.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gthmtulgoa.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtzhefouda.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtvpgmykwa.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtechaksgh.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtvqrmoxfi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gttizwzpzg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gteuismsaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtjipulmah.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkfalcfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtlrykhcgh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtirrjlsml.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtacnvvefr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gthrdpqeow.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtreegjxnt.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtfuhljdzc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixbhubid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gtgxjdzgty.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtpuwjpioe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtfgbksfrl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtdwrcmgcn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtymgtnidb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtzdwvmeue.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtgjkbcksa.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtwjltrfeb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtyiwnrqhi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtxfgvdhfa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtghktkttv.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtkdywydmz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtibozmkdv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtkjztcnmb.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtinmeqzye.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtiwszbqrn.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzgcrakw.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtnoxtzjta.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtyzjodnvt.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtmvpkysqm.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtukwqkkhz.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtiwmjodqf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtkgohtqei.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtrhorfmha.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtnnxuvtbp.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtphymohvi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtykrbwwav.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtflfaafdo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtkyuosodl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtslfpyckr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtkvstlgcb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gthgxgrran.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtexhnzoxz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtplpgwoxb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtryijqxux.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtvyydrmyv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtuujftcak.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtxhgulvpq.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmotwrsx.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtftqvyfyf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtbbcyxkmj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtmxgmyhtb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtcyammnbs.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gthwujhtkz.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtjuxvowky.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gthaejhxxu.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtgwfprrhs.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtfqiqlcgw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtknwkhjal.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtiekmweiq.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtruftcxny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtfbzvbntu.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtyowwjdjs.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtfgcfdaej.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihsslkog.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtqsttudle.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtknuvpifs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtvfdfvfpy.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtgomfyxjn.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtxmxrnwum.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtpzzsezpe.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtvxpolfrg.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtmhrylklq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtnjottvxp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtjrtqgepf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtgjsyvirf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gthadtsobp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtjlsihvei.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtbnjbteba.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gtufjlilbm.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtiylasyno.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtsbpxyvwp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gteacaafpt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtcczzpdcz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtwydqvldd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdsficig.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtyqyngpni.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtyjnurosz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtuwwagxcr.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtutlorwgg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtjvkioacn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtrkrueveu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtnrracvfn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtkjdnvugz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtcjpglpct.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gtlplfojmd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtflwohtrc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtrhbtnrub.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtrwmqmhmo.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtmwhojdbq.html


<!-- 参考信息 -->