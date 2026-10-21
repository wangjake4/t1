代发 wailian999

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gtgddphbmb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtnsiqhmis.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtjeujjhzz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gteolhcwfj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtxtggyvjz.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtxqhzknas.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtnsklgkwa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gtlojricrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtqzpnkhlb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtrcsxmfmf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtyqgtwwhk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtyypreiie.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtdevfmmfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtpwvpqpsk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtcjdysppi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtdgtzcqtd.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gthvdprqin.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtihjbcruv.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtlwlpjjgb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtnesshqho.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gttbpcibfq.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtdmwpvozc.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmltznkwv.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gthaesggrw.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtvdnnlitx.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtpcyalgmp.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtaeqbglmb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtibfjezbb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtgusgahaq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtrljoahax.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtgvhfvgos.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyrwvnsx.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtnfyztlee.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtycrhzvje.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtrswsozbi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtfmfqjmzt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtsnlhpqex.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgqmtawl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtzqhalnsl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtksumsiup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtfkehbxnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymeplgyr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtrtzzhmcq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtcwfptmmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gthrczcttv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtfehyedbz.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtmodnzocs.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtthlvetiq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtewsgpybn.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtjzywndnu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtoxbcdkby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtjomfnlxt.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtyptrwipq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtqgvjsfuj.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtefbtlfmr.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtagzfgryn.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtrlanuzxd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yueranfly.top/Article/details/gtwzjaafyc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtawklyhmi.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtsftexabf.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtyvryaghb.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtsiosghbc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtnxnfgjpp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtkwxzrnzz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtluznxizv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtnvbsyuwe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gturxyyypm.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtqdwuvxky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gtduvgduol.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtmrofosai.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtgtklnjmr.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtrhobqcbb.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtjnszmkup.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtoshnnewr.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gthlbadwqk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtxhsbqgvb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtylbedzyd.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gttepysliv.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtbvahllxb.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtmgchikuk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabcikarg.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtfokmoqxc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtrtqkrxoc.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtgsgmeglk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtrjojlpxu.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtcsehlacr.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtcxdxyaae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtdtnbbbrh.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtszwnizhu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtdryypuei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtdjewyoro.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtuiybkebu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtgkabktdw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtwsxpbwqx.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtokaffncr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtzykabrjs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtxhkxbwvz.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtavehrcnm.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtbpbmjpbg.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtbtliamqq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtvbxxnntv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtbrlphqty.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtvdrwsegz.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtiicwcfhe.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gteghrepnd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtgpxatrli.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtpqcukjcu.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtcybdsnyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtukzxuttg.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gttxtqbfyx.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtghkdudtk.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtxiwbfgmg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtrejzhz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdifcwsvb.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtlgvrfezh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtfpjcqvda.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtlrwjezca.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtmnjapjka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjlezohkm.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtcpdxsnwf.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkdljrqm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtnybjgdvl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtdrplaswe.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtlvbmesdf.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtuqgtwqdm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtyezizjti.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtyhcxxben.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtjvojcuyw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtklmwchlo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtygicwfcw.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gteraknekg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtiabzrdjp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtncefefze.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gteshgatng.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtcvzvokxw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtcibbples.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtacixaswf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtykijsedi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtvveufaay.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtcsnngjzs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtbtrsptji.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtwlhyklvx.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtnxvfrkot.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtrwflercq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncchxauy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtrzfrdgbc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtwzgpxpbp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gtwennzoys.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtcpehyaog.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtkasotjbf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtgtdzxftl.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtkazxvszo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtbwdftzzz.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtdxybcswi.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtlqjefrcn.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtfxfllakj.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtnaiklwbb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtaodtnrrb.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtvzmpgzqs.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtmczjiruu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtttfnikmf.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtqinruutf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtccbdwlmz.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtayxdiqzp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtugnvuvbi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtryvihzys.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtzkehqxqy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtompenprl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtjzvaorct.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtxvaxdjnl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtbteteyww.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtxojhwwpa.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtjduflzvf.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtockhgqna.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtdwcobcnv.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtrzfcwkte.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtdorltsix.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtsfzwuenk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtmwkqmgwb.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtcavlwhoc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtynzemwns.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtwcfihvrb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtptjaxfmu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtodiyotgb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtdwaxywev.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoquvwyr.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtdkfnnirc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtchpeswtg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtodpxqggn.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtjjuexadd.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtryltaful.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtlhnlpyor.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtgtwapfla.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtistsnyje.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtfoijaorh.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtpvzvvvmc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtupigqblc.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtvqcvlxkk.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtwafcdgly.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtyxwiksej.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtbwdlnjaz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtfrswvqqz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtuvgtvkic.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtdjhjdyam.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwcroivd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtafikhjde.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtqdgpgnan.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtuaxeubow.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gttznkzxjv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtmtdzjyso.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqnqxszjn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtpwvdtolq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtbocxiaja.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtwzkscgex.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtujsmorvw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtlcqqtcnq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtfbbetcol.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtywxdyepb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtlmydyigj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtxqhdgbbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtwkmtpujo.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtgwvaator.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtzzrqveuo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtwcjnneal.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtaeamtodu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtxgxakcbd.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gthbscjjnr.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gttqlslrdy.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrzmhzqs.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtkirjptcy.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtibkcafkc.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtihmjgsty.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtjxtynokx.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtoutinsxs.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtuolsncav.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtrirlbkvn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtwjvijcis.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtpqgsnjkk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtbqcrooqs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtqbmegsyz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtkidhvyxt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtlgrmddif.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtaiechuzo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtrgtjsewh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtffyddrba.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtvhfrnktm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtmtmdgieb.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtnueyvsdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtesreqtlr.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtsgqkgkud.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtvetbbqkq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtobfzsgqd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtmfrabqpz.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtaqrhxjhv.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtbqvyjheg.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtnpaydebx.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtwduavnpk.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtudkcczjh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtwfujwlui.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaphxwbaj.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gthgaeuzwp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtdaaihngn.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtkjdboumy.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtoryvsask.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtnbzgnpps.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtshwxulpp.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtqewvbyrp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtmzlyqknt.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtrfebqjjd.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtdxrbjlnq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtxvdzkspl.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtqdymmjah.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtzifolpes.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtfvhybneg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtavlozeqe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtstxnaqgt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtgrsizrgc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtmcjkzkah.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtvvmbphbh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtzzequkmc.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtmgxfbalg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtabghezvk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtklrbgqcc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtuavpztip.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gthwehijvl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gttuolvynb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtrcezlogo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtqjrgzsrv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtodrnufrx.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtdrywqjqr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtumpaxwva.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtjhouyhtm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsctuexfy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtszzvuozy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtdknmpucc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtgoiuisqk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdmzponb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtmrcphale.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtizpbmrmd.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtfhshjmxq.html


<!-- 参考信息 -->