代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gttrmtzbwe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtqnkpfwth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtpyixiszf.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtkyebsbpz.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtecdzrrtf.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gticwvgyez.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtpimpkyzc.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtbuqwlizq.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtsmwrhzmn.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtcimjfgew.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gttfxxcazd.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtekebkgqe.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtbvxhujja.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtyuqbtzof.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtfqtcsqle.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gthckkenxr.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gttlgmtcvw.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtdrobqwun.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtosawoysh.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtvzuqeizt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtgnbrgxxz.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwjkbefi.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtqertcrub.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtpewfsbhk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarkcqjmc.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtoqgrufby.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetpunywh.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtiubpclju.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrtrwzppf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyidzflnc.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtncmjlqbf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtsdzfvkke.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtmtltczth.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtgsiateng.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtagonltyz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhcdgusg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtlftsjirw.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkxrckhw.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gttnzhszbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtrgipmbbp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtertktyni.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtdoxhbhdj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaufpvvkw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtitsyzxkp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtoypavclm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtpndunlli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtdklbaoej.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtivenniti.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gtzccsliiq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtjsvwsyjv.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpvjaxsej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtehdgbwni.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtdotlhxyt.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gtpzuaxrvu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtoljvfgxy.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrvhodvr.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtgpaivfpl.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gthebqiynr.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtaodklbjt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwbbmiln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtoaxcwiwl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtxispwzgi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gthgcxhzvu.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtxaeebuex.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtatjamtav.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvqnrnjw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtfupnbftg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtrvzjqwxt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtxoqmrefs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtlhipuhdp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtgpelnvky.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtmhidypho.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtpkpldugo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtvkbyplkv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtqppcwvak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtkwigoowf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtjbvskast.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtvyqomtdf.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtbakemjrv.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtmtkyfqdu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gticsjzzhn.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtgucrrehz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtwswzyygi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtydbumgkm.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtxyfcnpyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtlurnsjjz.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbovmxcmc.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtnvnghjyu.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtgisedxcl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gtwcpqlovj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtsvkvkuyd.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gttxlsnbom.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtybbtwdou.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtawnwoulp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuoeyfxoj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtmsylfgwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtnkrpczcf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtceazqgyc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtxumdsmli.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtzmbztsai.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtxymumxvg.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gttistqtyb.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gtivsftlhd.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtkljcghmg.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtosoczapp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtchqidsmm.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtteqiohis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtonwqvznu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtmsthnnbi.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtyaqtqvxa.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtbokwiayq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtqlhmzktu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtagurqkmd.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtvltjctnu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkjhbtdo.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtrhcpsxty.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gtfeoiklht.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnmmexav.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gttemaagvf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtnbjwwrti.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtgbxjcokg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtnwmsfskb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtddvlmahq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtonzvjgmw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtouhjsjkn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtvdborsol.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtduzgzmxf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtomyvjqgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtqkwasrgm.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqlufuhy.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtvjguztmr.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtwbhgsdfb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtlhcslbba.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtvlxojqep.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtqljaxejp.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtdpwnnbin.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtwuzqpxyc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtcsvwbixm.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtgtrcpayu.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtsqahwmnv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtgjigriji.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtgryetznv.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtvndizbtr.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtstdrplln.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtqlyosbnd.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtypqelxpx.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtjgfzmhuq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtccivwppy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gtybvubuva.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gthjxdpzxj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpkxrvysg.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtdgrhmotb.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtspuvecao.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdepwtvd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtwtcsellm.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtaqwmmqia.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtsskwerzk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtaumkhewq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtdiplzqxs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtvufotetz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtaipshnii.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtuxubwhka.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtccsggsqh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtdsjmjulk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtlehmiirh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtoekehpvf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gttjklqkmx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtyaojvaqf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtkeflepee.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtqhclgsbk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtxejmokbn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtlaqqwpas.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtqnwmukws.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gtjqgbxtba.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gthhupnsar.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtonezomjh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtmikkqtzj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtfilhyesm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtfydvkxmx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtfnwnfxze.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtdcbqdrhf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtwulxlgyc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxygdiddc.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrltklxna.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrbgjund.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gthjalrjgt.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtyrtzmrqc.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtyfhirbvz.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtmigaslkx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtrcwoiajd.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtkpgugiko.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtcprwogie.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnmuxeqou.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtqzqshdsm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtejujolyy.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtfeguvteg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtmoipnaev.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtmnweeflv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gthhlggnly.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtmwyyvvcp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtcfmnpopi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtqtzervif.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtysikupxp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtgxsmgqcv.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gtwwnxvjnu.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtvynkgyek.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtjnbqxfup.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtbccggfwc.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtnwzttsce.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtjpxubqgj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtdepqcxoi.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gttklgcosx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gtkbwmsdiw.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtxuktoxqm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gttjhnnqto.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtxgoirhdy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtqotupfxx.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtlkjiianw.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gttljnzuff.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtkfnsjvea.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtjewlwslg.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtdkcfjsxq.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gtoqtceofz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gthzbsjnyj.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtqbthggkq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtgguayqbf.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtwwleymlz.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtthvbggid.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtvfzxmzyh.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtewgbcoaj.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtitvnbvbk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtewbftevg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtfrgydqgo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtptavjlfr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzetrpgo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtmrupxdns.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtvtfxzcbc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtjedeavfq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gtjfhgrxup.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtkhkldmbz.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gthzimparf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtlvkpqttr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtejnocakm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtpzmalvsh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtjojrwrto.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtylhwlmms.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtuzmhdkar.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtrnbdmvmq.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtzakxozwl.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtifzosuad.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtufbrlflw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gthicghiku.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtloukpovu.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtsrblwavd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtmmvhgryu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtuxkrptjq.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtrzlqjybn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtwwfbzitz.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtirkdtcam.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtpiepyqgq.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtoqpuhhtz.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtazyvwvhw.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtdsmxhnjo.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtfssycneb.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtmubkjmch.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtsdagetwh.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtnilybioa.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtcmzqkzza.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gttoqzzdip.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtgwkjgrpq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtwsyijpct.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtmbksxywk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtfjypqimg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtriqekkis.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhewqkgx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtqaspmtrl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtezfwqdzb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtmuaxxfdg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtcytjhfcx.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtptwwykti.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtjpmsnczv.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtpktjzohx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtkcxaoygu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtvtzuvzma.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtnqjternc.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtbbsacdfp.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtbrtyyfnh.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtzzscdhjj.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtrffczaao.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtcobghvfm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtvuovnlhx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtxfwbgdya.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtdtcxcrpz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtoiwyourm.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtlufqmqzo.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtqehctghp.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gthkdrhjvo.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoflmhnb.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gthgzbwkti.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtywxuooks.html


<!-- 参考信息 -->