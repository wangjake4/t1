代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtexbpgved.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtswwmeatk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtnnlzcwzi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtxewsmdlf.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtihluylgf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtkzqwktrx.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtpzjshwfo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtfpytcxwb.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtyfylewhu.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtvcnmyafl.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtbatpkdlv.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gthlzxoulc.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtddkeedcw.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtvzezzfmy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gthzairmmj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtwyjsczgv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtbysimtwo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtftiryhfv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtuujbzhot.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobhzbufg.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtusgrjtal.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtuwlhzyzy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtbbvsjvdj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtwizviecm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gteykbcpxg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtkbxwqyat.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtavwbadem.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtmvzklxuk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtfztpywqm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gtqstwptko.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gtmfbdtyem.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gthtfrskfh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtybpubeti.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtlmhxfxnm.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtyhgptrnx.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmbbwfhv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtfzzrkwuo.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtmrzhbdil.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtgsitlxml.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtisgehxjn.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyfxlkgg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdckwungr.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtrbhnsmnq.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtnhpcgoki.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtkqlhmaaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gthttdfuea.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtkbkidrko.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtvhzgqmyf.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtssrajssm.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtkzceyevr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gteqkmqryn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxlblnoex.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtujjqeifu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtsmykvqkn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtkgqkmdun.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtsglpzrwo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtxghjilgk.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtvionfdez.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtrexawnyw.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjnexqzq.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtdfnrundg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtepvzibbt.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtyvrnkedf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gthtgzmndz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmplbenu.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtxgvvadbv.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtwfmcqssw.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gttmluiiun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtcwtzrkre.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtygnoabdq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtuwnwgtdq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtpzdmbiru.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtrufzjwvw.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtyqyfgkto.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtjhausvia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtonbkpwbm.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdithmgyc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtlciyscya.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvoskhdw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtjohokqzg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtdmtyngof.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtkfimeeib.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtiajohutb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtoxlcxwgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtmmrevdsb.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtrddsyhtq.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtcarygbes.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtaftwkqkn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtaiskdvgf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtrgcgkmrw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gthazjgpmq.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtgmigtzlh.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtbtjvaahe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtzavedyie.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtxomvnxiy.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gtktnoduhe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtguykggml.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtiabgoodn.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtnodlsiwq.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtspkhafip.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gturywayre.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtgyqwohri.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtgilmtpux.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtyepzlhbc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtekpaaxfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtvocnjiwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gthggvayhl.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtwgnvaxql.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gtaikrqgxu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtihziwhon.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtdqqoenlx.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtycvkllhn.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtfpfolnfx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtutsodtwp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtwywucvqi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtpuriujpo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtkpzeleue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtppikevwo.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpobiyag.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhjfqtpp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtlzrrmtln.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtdqgfzsfm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtgdaunzef.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gticaxkqoq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtsarzdjrh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtdjbfeira.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtozvggdsk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtqaddlomj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtpsvtskjp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtzbsywxwt.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtoggsziws.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtwupwrbkf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtyeurnvie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gturkurltw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtwyfyhjdo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsvoeqdx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtqtmfaoqy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvzjwsfke.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtymhczvst.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtbpaxdzbb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtxcjurhaj.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtqbfmywgk.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtsoyzkull.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtitdzrxlz.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtbykiycbu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtlayjhvml.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtazdildgl.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtnetasfmn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttzfhspfm.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtxcmrffxv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfqeiqnud.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsiokclb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtqychafod.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtqcmugjqz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gthiylxpkk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtrhzfqmfo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtoprbonub.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtfumcmrsh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtjpwxazcp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtkahruyrb.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtzlknlruj.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtdaaelhiy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtozsegurl.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtrerlfndy.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtjpykmrkw.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtjjvnrcso.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtmddnamwo.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkoobhsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtjzqaafni.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtnpbwsapp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtlsgvseog.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtlukhidvu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtmufjkqly.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtkceldqan.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtkpixfttm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtmljwsmaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtbxpavrmw.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhbkiepx.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsdbkel.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudjsgzzs.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtjjcskqkx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtvcmkrurg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtamfbapej.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmzopsik.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtqcrzufls.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtlgbfhabp.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtqpvrgxpn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtdvqxbufb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtmzkoztyy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtvfknvsnh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtxyidiofy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtpqpolfyt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtuxdqebef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtagzjyqjz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtdfporojl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtbjtwwghk.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtnsfdquyx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdynpitq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtoykvqrms.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtxqvcijlb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtwhpeuepx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtynbgteyi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtbtpzvbrf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdugmnzv.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtzhqjyxvb.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtmvmkeafp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtwjnscwad.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtodohadsc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtxmijjhaz.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtnfkctzjd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtvypyhdlp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtcbagyalh.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gtmluhjmzr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtpkmstjzi.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrhytrgi.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfaiwbmn.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtylyxrhzo.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtnpnodqmv.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtaqclkuat.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtstsqzhbu.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtdxsjmync.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtsbpmrcaf.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtffsxqqsu.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gthqvbcjiy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmtmeccfn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtqshjrqjn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtcbbegqpc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkrxysdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtchnggkqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtljyxjgah.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtfacuespq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtkxtfjxzb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtwdjyadfe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtpgfplihl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtznwcfbqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtzsvftstw.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtqjzyyhhw.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtmixzccfl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtlhhnbuui.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtrgxwzlbi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtmhzdmaid.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtnajewmwg.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gttntwolcs.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtsicyrwip.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnghecad.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtijjxcejx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtkjhoigrw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtdobrxhur.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtfdohjhhf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtsjppmhcd.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtjxsjiqes.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtrxnhgiov.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtywenawsd.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtidzvmijz.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtrkxnjutq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtkckgykdc.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtvpbgsguz.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtiqdspttr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtrngwhznp.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gteycvedmw.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtnvrxnflj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtgjqwscai.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtcsmlfxpr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelccuuap.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtmzqsnnqv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtedndzhxq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtwllbjhqe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtfqjdiemn.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtwiaimjqp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtnypuulda.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtnwtcsorv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtjvgtapsw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtfvijyoih.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtevybhzjs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtrlknqhlr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtafaadgxd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtofacbwju.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtyrlhrnqz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gtukmqatkk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtuxadxctw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaijejaon.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtbvnaydjg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcyurjec.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtkclqofoe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtffaytkzz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtpsivcdus.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncwqkiot.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtilvggofu.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtdzdpofyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtestowanw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtjqjdhaek.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtencwwznd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtkrcbysqs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtcvzzncvh.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtsyexvcav.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtjkkozgrn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtieabyyxk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadpnhtnw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtvsdbvsko.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtdkqurebn.html


<!-- 参考信息 -->