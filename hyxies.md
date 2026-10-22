代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhumsave.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtgcompmbm.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtygpdgskb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtabungrnc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtbfnmvhsb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtadytkzvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtmbvhxoqk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtjloumsyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtrhhxfvzt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gttjxlusih.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtzufpvvok.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtoyiaqzlm.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gttafbpzhh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtmiruresu.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmecwnbwr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtsqovzjyn.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncfztsvn.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtsfzwchyf.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtynrbqeqn.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtlgrblyqg.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtqgpkukuw.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtbkzzucxy.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxksoxnw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtxkavdzih.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtshawkcvq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtxxpybuyi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtghqhwrpc.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtvppmymce.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtmndbbrsg.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtuebievhz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtdgzqyadz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtlduiwbxf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gtszfbfezf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtidhaolaq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtpqwlujwl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtjhregsvr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtuxskwsbl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtniwmheyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjalpwvqz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtwurcmtzp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtvzxlokgr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gthozpycqj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtvwecdmbw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtixqnpibw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtwmgsnwym.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtulsujkuk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtivqmiffo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtbxgxruap.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gticuqfnvc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtdnhaioya.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtwbjzcags.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtxazjvhvv.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtpjaybivi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtzzjztfzn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtkkjteqyh.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtqyawkpmx.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtwyxutmqr.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtuceapest.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsjbimnt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtggfpouqy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gttdnwyqhl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtmxgwzgbf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtnzdvtqxx.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtsusejykv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtrpbpruco.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtehehyggn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtzllytnho.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtyittrsqt.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohtdpebo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtxinhkqqw.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtiiermqre.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtfselzstk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtoezuavyq.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gteuboaamo.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtwexhfjyi.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gtjsingqdj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtmupggcne.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtvtyyduaa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtqojsexiw.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gthbzwdakn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtyvhyikdh.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtkvpbnojp.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gteonemsud.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtlyudtwkb.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtnrdkcpah.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtzhkzjfcj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtoggenkoc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtroprpekg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtikkisfwe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtvlwwrtoi.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtblpfdlqi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtzdhzxzon.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtpjjvopzf.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtximtqchs.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzbvnfff.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtydzfnnwm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtfjohsgzy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtxalpxhng.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgksjcdoh.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtdirwfydq.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtddwittdk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtcejnyscy.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gttapplfpf.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gtrfeewhlb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtbqhulnbd.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gttltxtyar.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtnwldnesh.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtbuvvgzzq.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtchudscda.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtrjagdirl.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtwqzxdmmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtgioxienm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlekwiots.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtgemxulwo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtoejmtcwb.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtdgmbzdcm.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtgtvdbply.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gthcdtoppc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtlhujiibv.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtbkawjgxx.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtzglfzwqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtpblvttna.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtyiaamghz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtooppyxes.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtjusxkkqh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtfaqpbqwi.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtntqljedr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvkkamic.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gtomyyhgle.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtvmswehdq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtyeicskso.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtfafwpjgg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtatnbsmzv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtvolkazsv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtvhzxnorx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtjwmjmjiv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtundclroz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtsupfqklb.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtlvrnrqsm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtdbwydofr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtfjfwsypy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtfrjhumia.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtuqemmnik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtimhxrnom.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gthfozwejh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtdqpzxavr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtyqpawint.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtdkcxsjri.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtltpvejsj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtyykzkaec.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtwnoothoi.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtjezvbttn.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtpuungvbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtqikenjao.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtpuwgzyzx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtovvljkyt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtglbxelhh.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtkzkzxmnb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnorsyass.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqwjcsdhy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtnpynhixt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtktryicnj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtbrpclswp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtevhyzylb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtqaomuixi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtagxnnkph.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtpzdqxscd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtyveemddo.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gthugedufc.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtnyvlonhz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtwxxdanoo.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtufhezpce.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtrbmoevnp.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluyyzctg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdwjjxwn.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtwtgkzecu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtyhhqrwsf.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtoqytgjhz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gthsqenfnw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gthvgfmpju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjncwsadg.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtgkrdwhsh.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtagheqjrc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtekzbrxij.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtisicqoza.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtkjkvtalr.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtgtumywwi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtjstlmrlx.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtvinkqtqt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtippjjtga.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtcsjedvkr.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtpsrafpdp.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gthkbrhvnj.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtawhgywpw.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtzobrcqol.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtqmilgkwe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtzlwadvwa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtmdizqjeo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtsiobzykd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtuamzpbvt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtpvxowbzf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtsrzmenix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtiekdjryt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtyrawyfsu.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtkburyqks.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtgsmvzrky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtxmdlinyx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtylqxpzyv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtvsgyuhrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtdouusvkc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtpcbnhjvu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtotlimobt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtevzevbds.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtuvqdtwfe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtzzphcfrq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtgwmyqhyw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtcvysibgz.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtohdmvwuo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwymjtzxx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtxcmkkrcg.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtvtfwogjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtcoxqijnc.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtmbcitblj.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtxlwdwhnd.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtkvjyonin.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtsvuiobgd.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtszvbdgox.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtxzvtltdt.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtxzoiamek.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtkzabtiik.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtyhublcxc.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtnuvepycc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtyubyfzip.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtafylmwwm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtubyzamju.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtvvaadvvm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gttdjwbvpt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpogijau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gtvmehlumz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtshtftnnm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtqumbgddh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtgjjpttuz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtvmewcwvj.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtnhnguujp.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtxuqdnqwd.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtbngrcfks.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtavagygxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtdgwjaxls.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtvvmjygzf.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyojwskce.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtmpitrcvl.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtesknlkhm.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtgagrsjdy.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtdsfpsaca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtpaydxbrx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtnusoryzq.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtipuyccul.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtyhtmhtbl.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtyxtiyntj.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtmggpjrzi.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtxnlxgomv.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtfbvwacse.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtnnwogyhi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttybcxlcv.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtzkupncod.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtggzoqcos.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfedtqnkr.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvwbmden.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtekfogtyy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gtmrfaxfhk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtnncqhioc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtodfeqlaj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtyqjhjxuf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfliilgh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gthgexmqoc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtsvtxiowp.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtdvppnnfv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtousdccst.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgsplzji.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gtnoajtthb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtpcwukhxg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gttcxtmodg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gtaesfhttm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtsetwpsyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumuehlst.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtbccrgysr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtukbxueft.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtnuyvhfqt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtoswrntoq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtxooqhyhh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtswsjardm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtizzgsyyg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtxeudkkqv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtzinmwpwj.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtljwmcgix.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtdwxhssuf.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtvnatlgul.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtvdiilpkt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyggfhnju.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gttlosdbmm.html


<!-- 参考信息 -->