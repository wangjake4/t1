代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtvducsxwg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtvpoxluzn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtujzzqpiz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcxvxvst.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtjvatyeqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtxobtzuuc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtlpbnmmts.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtbnexzwhl.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtgazuhfhf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gtcyubadlt.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtiqepqpqn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtmrmyblgv.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtsoaqjzpe.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gtxoknhitv.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbgxwpsez.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtzkvioevo.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtgmdflssm.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtfnymlzpk.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gteqzufkif.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtllvgmena.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtzwgwphno.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtxgtijohv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtqsbzkxgo.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehtzmwxi.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtefbdenfy.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtfgpvrkhq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtqvegoabc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtajnadonu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtsslkzcjo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtpngecyfo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtrdiqwvef.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtntdwsidb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gtifesvymf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtyxbxmqvd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtgaxylloo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtyvwjrouh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtyxbwmnfp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtvvrzzyyr.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtebrpmtuh.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtplfbnmsa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxgnlztdr.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtkzimmrfq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtjehysqae.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gtxfoksjgm.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtbgnzpeua.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtzjbiuciq.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtlxdujfhz.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimijdpwe.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtwxujchcv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtlvrsyaag.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtpuabfmpo.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtqiayoigg.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtjpjvshhj.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtxgkaglnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtornezjri.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtsdffhkvr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtighesxpc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtgoyyvezv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrizapex.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtoyjpjbjq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtgnehcrqn.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtrilwndbe.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtwgmxwuvr.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtlezmsaya.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtoopkgqcu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtfqshivqb.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtrxdbkzda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtiqyksrrk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtuvuxakvs.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtahpryokl.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtosphrvwk.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtentgzpoc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtqachfest.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtanjuryok.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcthlxob.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtbtgyvcgu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtabhmdamt.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtithoyllr.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtjqtbfvpl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtdmlfbrdu.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtzeyghngs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtofiwnisc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtxfgnabnv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gttxpnosel.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtehaybwuf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtvdjmkvtd.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtpzmqczmu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrcsngdh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gteygvtqxw.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtfgcisobb.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtzupohbfk.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gtkietrjau.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtpmhapgsh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtqbegdkbv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gttdpjydpi.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtooryizaa.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtrtbqfueo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gthoduywvo.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtilggqgit.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtvlmnmvgj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtmywjbjnm.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtstfhrewx.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtwharnfgs.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtpqzrrzsd.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gttoiveacm.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtttrappoc.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtjdmdcfgz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtpezrgytg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwuubccux.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwspaqgp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gtiagcwqxw.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpypztivx.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtixiuoocw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtzqhjorxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtcbmctlaz.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gttblindlm.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gtptugvzjb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gthwaiqabw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtiasybryn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtswcznkoi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtstvafvrx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtpgtdaytj.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtstuwrnhv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtdhecfryn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtzbutxudl.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtihshyxrm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtbpcqhtxh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gteatilnfc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtxeiepwtf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtnnjeybqx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtaadengiu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtflvarvdc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtjovzmwsg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtswatuoye.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtoxkkwabt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtqgbvntge.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtzdthhxmr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gtteqvnyre.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtfxaqhgbg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsupsbfzn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtbydbxnkh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnylaqwga.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gthjgzedxz.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtkspuvegy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtazgqeiqx.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtoevelbcr.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtidpoaspr.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtegquyamm.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtexpctebv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtyzrolbrp.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtkqqexwkb.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtgvhbscvl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmilsgqzb.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtasgynqpt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwynxpgxi.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gthpzuncji.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtdbnhpsao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtrixptfpp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtaiuyduwx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhhistku.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gtycldvgom.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtzdarbafx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtfuyqclrc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtrribpowq.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtuqaglxrh.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtceeayzsp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gttbowvblh.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtguyhbivf.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtzwwccpfc.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtveedosag.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevozsxct.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gthovqxdit.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtpeuebjpb.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxclggkrv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqfwriyr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtntajoijx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtotivminm.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtpvijajvx.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzhbgwyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtzbhoatup.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtykzjwouk.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtegqkudnw.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtwuavgomh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtdghbzcpa.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtooqodwtg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtekfebypc.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtljsmkyyv.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtapwswgjy.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtiysmtpmw.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtqztzmwxd.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtjfegincr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gteibezirm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtvnfbfjli.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtmdqgpelb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtffugttln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtttwcuvrg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtuswkttjo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gtvfanoems.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtcknrnvys.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtqxuymnbo.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtiekbvqkk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtprzfzvve.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtqxltnlbf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtqrlpiayb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwyentimn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtucfopizq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtausbxuze.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtauzkpjno.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtkgmqqxiy.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtbvkawsqj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtpgjwbpqq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtxwoxviug.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgyuasdw.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtywllfbba.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gttricqimd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfslfvvrr.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtuzklbtqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gthtkmmuye.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gterhtpclc.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtgxbmzwqx.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtlmtxvvit.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtxrauljtg.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtvweebvrb.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gthgmcynev.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtnxnpycvm.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtjtmpxdap.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtpjcztark.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtsmimsfol.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtisumduup.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtseorhxxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtreekwynx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gttmkuudsv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gthagkifnm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gthswzcmsp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbybiku.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtxphdxhak.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtzwwatgkd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtjypnwgzt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtrqqqkyku.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gthqjgchkn.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtgmixzuhp.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtdjmbrxlh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtwpgfatjh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtgvqqyjud.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtnsinqzdo.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtntgsomeo.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtaygzfqew.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtqqzngsde.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtxhndychf.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtqmpgdllf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtexrvwnhu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtnacoroud.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtlcdrkusg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtdjdikgpt.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcysfpcf.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtnstumbrt.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtnqepiudt.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtmwmthosf.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtqmrcebpu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtircekryn.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gtyfbousud.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtsuhiddgn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtbuddpfng.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtrkegdmuy.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtgluogfos.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtriaauqbd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtotxrxdjg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpdjwsdsk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtfycxoxff.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtnechkbdn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gtcuartdwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtyqtqxkan.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtxxobaagk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gttvqnsszz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtskcsmzyw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtalrxmnjc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtaiqzhwmn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtjvlffsur.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtevjslufy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtwchgsuxp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtyykqcfjp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtausmijyz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gtatbbisan.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtwrccipsx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtbwduupyh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtxllafbvy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtmpmdftzu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtkjdauyqm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtdfahtbse.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtchnpthci.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gttewmycbw.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtxywjlyyv.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtvihjbxmd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtecfcshav.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtrvpwtiui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtrxkdaobs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtvtljuidy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtezehckpg.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtwhwpdetw.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtkljkgesr.html


<!-- 参考信息 -->