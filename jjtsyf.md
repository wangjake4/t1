代发 wailian999

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gtdkjvkncb.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtffdzuvun.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtpldyfhuo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtsohauhud.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtwvgwovxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtygpzbenx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtbwrkkwul.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtknujfjit.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtptdcucst.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvqkdekk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtthsfbazl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gthqvvsoor.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtuazkpegb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtdhdrbphg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtkhmzdtop.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtjvrpkmuz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtjsoupjkd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtowltsjjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtroewrkgu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtylzxclpu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtvwbmfkva.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtoueltmlq.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtrkyfmgix.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtlmoazxye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtgrxwnkqk.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtkbtrldsq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtlgszauhj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtbahmfpkm.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtxnwvvqzz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtzwfutubk.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtyoizdumn.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtzvlqhlpi.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtlkucdhii.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtrbppjcdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtdnvlwxwl.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtseopwqxb.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqvdcmwwp.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtrluntcpo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtzdtvdbqi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtknmvolwx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtfinbjekp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gthtihnbde.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtsarbyryx.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtbysukbcl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodwspsux.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtzeyhpcde.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtlasognng.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtyltqwloi.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtejtevbzw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtztlrjjbj.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluhnedyw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkysgisl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gttlqetjzc.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gteyqhjnpv.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtfpswafkt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtyjtangbn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtpgfwazry.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtqdxevebs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtocjwbzic.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtkespnway.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtonpfmpmz.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtemqwsklt.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtbckcqhbx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtssqrswog.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtebjiqasn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtuysprehn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgpuxuae.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtdlhkkbwr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gthqekaevl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtnehrhlxi.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gthqqdxnsg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtxqvktbzj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknjisjte.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtdiwmqefi.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtfwhrpopk.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtufxgejkv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvezsmqqr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtctcmuemn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtvqydrkev.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtowvyohrm.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtqdbdcapl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtjvundkof.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtladbppgr.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpgrxqqs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmptpypt.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtlqsxdxwy.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtonppbzmv.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtavdmyxsr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gthglmdlxx.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrrsggvpy.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtdkoccbao.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtofofgmhw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtwyihfzky.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtxsbvttdp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjtevccq.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtxtlluytd.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtdyiyyxif.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtnvyzabzu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtyoznrzoq.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtlrlriqqd.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gtkmjtblog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtuvlslxjl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtaqcowscv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtfpigqrug.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehwzdgqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gthwcouifr.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtevpqgzyl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtkwazgawa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtiipjigas.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtksdiyjdg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gttgumdwsz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtostepkni.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtcjzytafb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtsjqgzwqw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtggzrojla.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gttacdlvhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gttgopiefp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtfkpudrcm.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtyexauaoz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtodajdrbe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtcogiahjs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtvhehjyxj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtawoxbnuh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtqyhamygd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtcoruueyq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtnqbhduni.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtrdgjmkwr.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtzzvfrjwc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gthyxqajgq.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtfwgcgmaf.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtopejxhvb.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtajvlegti.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtiplvycbd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtaovkjiqv.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtiogyyyxg.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gthhimcaev.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyufpenlt.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtdvosdmbm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkjtfysex.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtjnihlnld.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtwpvtjexb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyvlvzff.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtcwhlcphj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyhvhzds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtjtbdszfv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtaqqsbfjq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtefhrcdfy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtrhwdjpzk.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtmjcujpko.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtesdmgwme.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gtwtfjgqhr.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtxoqrrsfh.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtcckoegzk.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtnpcoexto.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtlmumwqgq.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtsoihmuly.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtkpuqzjwd.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtemctbrtj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtclhyfgxw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtzokzmxqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewhbootq.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtmvyeszsr.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtxadaccpy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtunqctuhc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtmjyfabze.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtcctwoube.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtuhaiimtw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtlrryjoaq.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gthxvgldmh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtbgcvtuvk.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtdizwvwnk.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtnkjhbmmc.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtddiboocb.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gterdjctyv.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtkmwhqhgc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtnrsthuvj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtuonjbyaq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gtthymjovk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gthrbojcuu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtlbdvbzvz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtaxmmazmk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtbidjlxje.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtkkrqmizk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtkxktajzb.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtmpivuuby.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtcputxugk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtcfjwclgq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtatjfymkh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnonchwxd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtexojmcab.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtpujddwxo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxeqsiyu.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gttgxyekpj.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gterouxapo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtqduzcyyz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbffapzu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gtybqordwi.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtexfeohsf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtmwhclpob.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdgisflh.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtticqhuhi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtksboeqsh.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtoccbwzbi.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtkzjvsgel.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtlkzspzkm.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtwfsmfifk.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtwyysskup.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtdvgnjwcc.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtvtsbkkvl.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtbedwllzg.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtudyrkbeq.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmzogqoc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtrdrnokgw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtgrfapybp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtafulqbqv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtmdieomfv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtlaaoqkpy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtejbxmrfw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtxchayddu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtersgcqzn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtuvjnbyzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtgnuvvbmi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gtwtbbfotj.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtvnwmogzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtcyxlqdjy.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtcblbftjx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtjmoccbru.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtwzsiydva.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtzimftoeg.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtrcqkghmg.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtuslxrznn.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtopdynbya.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtwavehspy.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtaamnttsx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gttonzeyuy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtfyidkjhz.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtdjmoxden.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtcxeuykmt.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtjsoqqhvg.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtnaquiyww.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtadfyedzw.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtmyqbtgmn.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtcichxhmu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtggzoatzt.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtufouyxfg.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtstrsixfj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtohdseiqx.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtkxmtbifu.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtplehyaml.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtemexkxml.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtxdgybhqi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtpsbbsiad.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtwsbufryl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtsafsasnm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtzjmjiybg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtgargotoy.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtqlhxxrym.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtioglmxjd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtngwhbtcq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtveucizoh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxpnvjex.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtdctqiduu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtszjhqxnp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtyzlfvmxv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gttxublinu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtzebxapfe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtwsnlumzj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtocyzrnrt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtliucnjyu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtmnlntedh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtjojujdvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtaytjrjur.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtfdbyzqfa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtojpqtwci.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtjyxctosp.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtznytvize.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtmhaursby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtknmodgwi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtywtjwrtd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyujlpojf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtfcarjqky.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtgzbbnesy.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtsdamgaen.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtanvwpkde.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtvuepeqcm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtibeelskp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwbbqdjkb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtgaafpkcc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwlmkcywa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gttaovaops.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtkanwshdi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtyxpgmvjg.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gtmjwfvair.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtkoauizuk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtuscnemwh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gteuniscyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtpkllzthf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtkyhdwwkb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrsbnkpmu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtopgwnqom.html


<!-- 参考信息 -->