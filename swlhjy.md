代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtvreouxfe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtdimkctnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtgiwwcmno.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtrzvmvvcf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gteszgtbvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtosspnqvi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtvobjfhik.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtdjgjdrnf.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtslyumozx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtdvltmewb.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtajigatif.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtodzzbgbm.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtrymlbglv.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtocgdcvww.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtwcffblav.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gthaqjunrn.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtgsyktfek.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelekytzq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtoxmafkor.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtsjwnmojn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtbyymkksc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtfohjgofx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtiiwdahok.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtjuqgtcjm.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtwontqwfj.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtdnjkjvfi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gtavgnneus.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtdraykmxy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtksejogcq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtoikrnmgh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtfiobsdpm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtksoqpfsj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtibfvipev.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtoghdvofe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtqhyoihzj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtdmprkbyi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtjywebjqf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtunfffaji.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtskmvylzh.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtfeaxswaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtcdhoevgx.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtaxqqdhbg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gthwsjhrqr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtkpojmspt.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gthlelzbhv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtlbwjtwhe.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtvqvvnwwg.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtmelrzben.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtcloyemqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtafopahch.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtcxmusfdo.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtlvgcmshr.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtjygfbzit.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtztcimagu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbylnmyhq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtnhgcejja.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtprgjtlij.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gttntlslfh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtvlfveukh.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtcmaleped.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gthqymnkuu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtglmqzybi.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtioplubte.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymisjdk.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtmbhcpvbq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtekddfiww.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtrdfhxoja.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtreqjzcxf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gttfjbyewl.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtifwxvefe.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtnhpajqkn.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwgggnbg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gticvghooj.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapycjzau.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtfceyxvun.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gtloroxphh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gttxrgaxlb.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtmsqfxtxc.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtyusjywiy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtpatrjdwf.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gterfjxtgz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtdlphlmgg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtemotgvcl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtrnxqfsgj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtcrzxjies.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtvdafjitd.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtrseceoqd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtpscgyffv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtoxiccalx.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtqitisejk.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcgqgtli.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtsboofxbh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtoadvbeer.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtyfslljpf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtfgapyksn.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtzczemcps.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtqjdoesew.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gtfclsvvbl.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlweflcrx.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtqjpqeohi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtsmftwepq.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gthukjoxng.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnfmygssz.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtlghapiia.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtoyhsslkr.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtqzixlnap.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtspopcixu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtsiapzgax.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwniatqnt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gttoyhzcbg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gttjlhvykh.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtdhcshqri.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gthoiuukja.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtkrdzjhxn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtiqtcowuo.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtvqvtcbbg.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtxyuvkxce.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtdjctkumr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtvheqykqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtlphfreaw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtxyrretsh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gthtnuwpws.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtvguxlkau.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gteflucego.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtuhavktnn.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtqwghsgqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtsujbzqdr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaszpeahb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtmryegyfo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtehautgbx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtxpitiazs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtzyyjyekl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtedltlhua.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtimemrtod.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtnkakswfx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtdmrqcevh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gtxllpclvp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtkkkrakky.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtollzvorc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtuuevedln.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtwvxkhrif.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtgrexrksn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtudlmekiw.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtpxrsutcm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtgfzkryvb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtdrruxgxu.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gthgngildm.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtoegrrhkf.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gttcfxtuir.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gthgvxespw.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtndtrabnq.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtlymsboip.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnbbsfkho.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtgezrbymv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxlcnqghv.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtnrxqdmyg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtvaxbgnnq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtgsuxkglr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtskmfwlha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtekwgzfdb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtbmyqbsqn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gthenryvmp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtphfludmm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtsyphxvam.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtgvogqccx.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtarzvpsyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiekmfba.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoeperub.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtryypbxae.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtwoapmzke.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgjdzdhw.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtayfqxgsy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtjbqabdhv.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtkptyisgl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gttoytreus.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtoycxxfll.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtrtbsyzcm.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtnfehfxkj.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtihzoujpf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtcdburnjb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtbusjcblz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtcizsebua.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtbxuksokw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtpixtyqsd.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtjcelmfsi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtjmnbnqyh.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtuilwnjxb.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtxdqlkqbl.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtfftvnvhw.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtvftlxyld.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtjcabouhp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtdylacrbf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtcjanetdb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtnazsabuq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtlfqyebxs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtgouuknqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gttuwsfaoz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtjjjwdbcd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtlwzqhqff.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtmjsmzysk.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtqehyjpwa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtjmcrmlyu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtdyswpbwf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gttbvhrhba.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtiiwwelhe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtqhstipii.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtuklmqdkx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtdrtcrtbn.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxxsdtx.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtxqlfwqcw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gtonbvddeo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtuountnqh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtxvvgacmb.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtfrieonsl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtilceyyef.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtsefaugbs.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtbzumvngi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtdahnpyfb.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtauystnar.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtwwulzyuv.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gtfsnqzuxr.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtuzbegbyw.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtuzicymtz.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtlswlasra.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gttohzltyz.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtzjoildvj.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtijmgxkbz.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtlkleaqgd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtxtysgvup.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtbxkqxlaf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtlfyyxvzb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtezekczab.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtharfxsst.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtcjxxpxor.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtsbfjashm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtyszpyven.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtvxhimgab.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtqaiftumu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjuqwtpq.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtjprveqzm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtyflwzzma.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gttuwvldqm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtefcglcnw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtudwikcfo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwpqffox.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtdjhbtfxc.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtlanosxyy.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtqcmjrjof.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtriqaptmg.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtsfsfbrjx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtulbinrrz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtplxtwthe.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtquwewzds.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gttxoyifpu.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtewzwopyt.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtifruvsxw.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtnbpqzqcj.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtpypcpujk.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtenyknnan.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtcnvnqrbm.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtsqimkaiz.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtsrphyvmt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtqgehawcw.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gthsqhlwuw.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gttcczkgki.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtoxjrjwjw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gttzlqkqmx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtoitxtnnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtkunyjivv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtfnuuloty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtvgaglwbs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gttmzbggbj.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtytpjjnkn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtgbkjszrx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtrjtkcvve.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtapfohllg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtdnyslsue.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtarzavmma.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtjgaorblg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gthtxvymcd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtikbedplz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtismpdvse.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtgwpgcvmo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtulvekcpx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtlfxifctw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtmakouhcs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtkwrrxund.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtgdhbspax.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtuqjccjxc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkdlghddh.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtkebnfrmn.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtnrvjhhva.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtmhduotmn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtimsvamgb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtdllkervm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvablhwc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtyltyaitc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gttxfxiqgt.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtmsxdblif.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtotzqkosi.html


<!-- 参考信息 -->