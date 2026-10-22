代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtsyofkhvw.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtfqgpxovn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtfusjftgz.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtlsqqxkhq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphpcmckg.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtmtltggox.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtwtbenxqx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtgoxejbxy.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtlwyidfwn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmrugdau.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtebqixpbk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtqmwvelbr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtyysmpffu.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtuxnibxgg.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtydgjfheu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gtwwsnmfct.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtbsyjehwu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtnkqvemjv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gttpyomyae.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtvivwkwfg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtjvuwfncb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtgpvsfilt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtoslallix.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtzsvlvrst.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtkpxchizi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtugpznziy.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtzjqdplzk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtznmsuvvl.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtffxewjne.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtooujipex.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqnljupad.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtrejjifaa.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gthotqnogg.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtgzcioohn.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyayvdof.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtrlpvavgq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtbaeeuekw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvusvxsr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtlokpoorg.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtbnwsldhs.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtyhsdmkqu.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtjgsulmkz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtdxbskqhj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtzivqbdae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtohyzbxsa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtogqqqvjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtepydttcw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtucgsrmbw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtfnksvupa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtcnrlgzoh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtmarebsnx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtdbticlhp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtsaatjcgi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtabeslhik.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gthewuszft.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtcsqewehj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gtgmlxegyc.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtufbzvjbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtstrordyc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtftlnoqwt.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtdfhnikut.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtuymkpvbt.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtevdspahf.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtuxxbtpzn.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtddkteqzf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtcuvizehl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtwehdjmrt.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtaymarvvx.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gttjajzepm.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gttmgjfpwn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnmjndvyz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gttzokbncl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdghiytlz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtyccxmnux.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtqqqwdocq.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtosjskdzi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtrbafjmho.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gttqfyddsz.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtqlwjypqb.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtdxzicqpu.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtjqucdygg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvufimunv.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gtdwdzgcmo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtvgnhcotc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtsrlftjhl.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgwzcgmt.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtunbdogpo.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gthnndbnlv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyrtcbud.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gthatucmly.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gthlrazipf.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gthdtrjyun.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtswnlqzol.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtbijoylcq.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtimizwfht.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gttzuxhmfz.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtucuzttev.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtbclktxfv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtxzjwayff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtipbytcrz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtqssyuapo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtutmxxxlw.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtspjoncex.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtyyatuuoy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtpstttpoj.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtliurroyb.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gttdfpstom.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gtnwguvsoe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtalgizjsa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtbandvrzm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtqeuvktcj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gteigzkzcr.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtozcgtlno.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtahngfels.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtnyzbcafv.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtcyopzmmb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtpumbofmv.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtcurzjcvu.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduzaabfw.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtpcjrsckk.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtlzzbjqse.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtaopfnqyt.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtdzbhncrb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtaluwdquu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtarrdjysq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtyudnqpom.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtiusphhay.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtuuvyvlwe.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtbfzqahbu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gthcidrrog.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtqiidkqbn.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtbjlyqrfl.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtknhvcxsk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gtlecxjpob.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtnxwnezum.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtltjpisux.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjzhcluo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtkfnprdez.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtiivvhast.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtgtesfnzo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtrpvfbmrd.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gttugoothz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtxbgepgdy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjutyqlpw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtltogotzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtpyjnfili.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtfkjsvykj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxwgarag.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtopuayhor.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtlqzslqih.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtuehkhbuf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtcurqfyfk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkzkahqq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtahtylprc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtnvicxicl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtcrkumlbo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtyvtbaung.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvpfrynfv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtllpjncyt.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtcclibmji.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtwuyjfepj.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtfxolbbkl.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtdfczrvoh.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtftyreqlc.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtxfujdeal.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gthisxluyg.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtolmaykmd.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtjkuttkbj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkfxdlrts.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtqgbzpqxv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjrinjgls.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtutmaanve.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtxdacqazx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtpmuixjjh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gteinrwewc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtvlicpqzx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtoeyqtxlw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtdjlohsrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtvsxdvgrx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtrtylvawp.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtsoqyqxnq.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtynzdvrhy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtiksfpqaf.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtsuywaqry.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtiqbybugc.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtjahlyrqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtaohisuzp.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtabyirtup.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtuufwvxdo.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtfmrackfz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtusdfetdo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtcsjmweix.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtukyhounk.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtiaryquba.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtqpkoopsf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtxmupwpad.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtrhimubdy.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gtgwqlofzj.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gttwjlefqf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtcipzdwmo.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtkpzmfjcf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtbxrchnxq.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtqpdskyct.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwknglbt.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtksumbpyy.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtixcsgrjg.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtuyiudywi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtoccqlyga.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtcbpitrqa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtnywodpsd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtkboqxvve.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunyazyzf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtvqxposbl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gttjydgohp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtalusctzr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gteyowceci.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtaprirmze.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtfcvnxone.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtetwsdhuq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtpesitrzg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjmvvllym.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtxrenkiyb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtruxhdrcq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gthwycxvqt.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtwcdgchxx.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtsbtphxcw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gtibxlounr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gteeyaczht.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtdanlitae.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtadcdkaxw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtoxkzerqj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtcerjlipl.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtejbblyww.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtdacepekv.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtvpqkrpxn.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtgdxfqoqy.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtebujvyol.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtzqwlujgb.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtqlcprriv.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtbpqisnif.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtqmlmfjbs.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtxathatnz.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtlqeuohuv.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtznrpltpq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtexidiquy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtvgjqtpgo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtctpodhcg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtlpdvljnf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtpwmibuau.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtjzyfwwxt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gtcflgnwtr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtxtgjtjwo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtonlclsls.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtacmhwlxk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtjqdemdgt.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtuiuiabfj.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtmlnsmnhr.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtmkxcspiw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtlwdnigdj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtwfzydflz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtzbgfcbey.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gteyevqyxc.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtgqobtqdw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gttviarnuj.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhdazftk.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtskqxljxw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtiufabifo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkkeaivn.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgfkuvtv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gttyyodhnh.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtdhykroyc.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtnjoxapdl.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtqmeuulbf.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtkyehyjhn.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtbyfoklpe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gttbovmbmx.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtjcnwzuws.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtscfiewwu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gthjaserit.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtekdnncon.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtbruyhyak.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtswtmdqll.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtwvungvrt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmwegjqv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtteawjuxs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwpbxkol.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtggmmncho.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsziwopqe.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gteacwdydb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtvljdcviu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgmazwxj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtuitauumb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtqwgiwctl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzereyvou.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtpzpmyttm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtzqazbdec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtzrqtpvqh.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtwxvmcrwr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfnkutgdj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtkopmpukl.html


<!-- 参考信息 -->