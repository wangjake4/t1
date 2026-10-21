代发 wailian999

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtauypbhfv.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gthhhzaapr.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtpskhzfpo.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtrfngtecp.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtauoiicxo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtrdgcogbc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpkaqmgu.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtuosrsjid.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gttnplyymg.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtdwacgxwi.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtgzceijub.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtewtjmbhi.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtekwtnvwk.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtfkezpkop.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtjhwhdluc.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtbqrrbkfq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtgnhpygje.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtzivqpwni.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtqynzefwu.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gthwvkfhiz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtrldqktxk.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtrmskbnqc.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtsjgpockf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtiodccdsl.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtqwilqrpw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtqzkbljzj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtxhhkbkwb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtulnawdlg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtlmqepthd.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gteujwuigp.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtqsirqadc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtajdgjuqe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtjzhgpaiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtdnxhkmfs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtgbklmrvj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtyfcbvhbx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtcsfjelfs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gteekqwhvk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtyhmmtwgv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtgzbhtruj.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtqdwrrdmx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtwciyzgsg.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlrgehjcr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtmuidwqxm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtizjdxkdx.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtixfbmjbl.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtxmznmtwp.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtwghncrur.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gthwwnanaz.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtejrnezej.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtdumcanld.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtgfefknps.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxzfgquf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtcckjqswe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtkcjrqbhz.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtwdoztqdu.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtabcdcgej.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtlsgpsdfh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtbfxuuugc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtlbyjldua.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtgvixexxn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtflzivivg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtyhspwsyx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtikongrnq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gtjarpkqsb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtuvyddznk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtbzszcrxs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtkyschtuv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtdmzdhkgm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtqoosvkkv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtxlpwairt.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtheevoenz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtxyffqfrc.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtkizfztjg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtxaovmxsm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtudbyagsi.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtenjqpdgg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtadvmehhu.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtxxqzwogj.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrbxxjhn.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtzikltfmc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtkosgycgw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfjwnbnb.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqejvrrn.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtjscvrfye.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtkthlqiuc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtjhvirtsa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtsqyrgobx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gteonthyhn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtivqqqidw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyxvwpbg.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtcixfvbio.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrvestvu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtnvwgzaln.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtjnawdgva.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtkppdvvpf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtzekojodw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdfdssik.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtrmvsqbkc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtzhbpdoju.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gthpkunwgu.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtzoaytlcg.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtbkyfkcdy.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtackbkcob.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtiklyowkk.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtlcdtfzhp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gttfoeuoeu.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtjgwxlfjn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gttfcwcurh.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gttzxysnkp.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtrezgmmuf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtfwsandbz.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtwacxbxde.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtqrxmidfn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gthvgjdczt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gthvvgdgqr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtwmvzqvra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtakjxwmam.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtymgafouz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtmdaihspv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtaucoqajg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gtkosfappt.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnmwygopg.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtcmrkbtxl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtbizcveey.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtgbumhpnf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtohhqvzac.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtzkstzltl.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrcxykvw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtmlolhfny.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtvgkflhxi.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtntnanyom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtctrveyag.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtgziqayxg.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtepxrhncz.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjsbulwim.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzzslwkk.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtshjpkvwl.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtekrvdzqd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtfbygcngj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtsyciwjjl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuwgtbzg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gthhaarxgp.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtgoaqczyr.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtpzynpzhy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtlayjysom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtouzwopic.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtjdaeproe.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtdbuposmp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtxtqbmsve.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwcgtsfp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gthgzrjkrq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtdsuwliwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtubuhgvsi.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtmlujbxyq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gttnskghgf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtqfujjopt.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtqexxznvy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtmrlaqjkk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtrzipyofr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkddpxpsw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtmaieowrn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtnutvshwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtlhrtcrdj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtcpdmqrcz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtlrvrymwl.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwpvcaaa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtityclwef.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgcogunv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtricghanx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtkicjgizm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtvdvioyfc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtixzlnqul.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxzxhwpzt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjjljdjrd.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtubsgauqo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtkyurqtbm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirsjslth.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gthgqginuc.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtktmvvahr.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtcvusjluy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtqkzdgkow.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtfrtgvibd.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtzotchjiq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtisfaqnov.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnqvrvvu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzcmpixim.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuywwpwe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtsytjylqf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtteisppop.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtglnmoocn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtmeszlitk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtalczlhed.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtqpgwbegx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtitgjynqn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtcqafolmw.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtslheuneo.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtchlnfsnq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtxrtqkazs.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjontoxuz.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtwyhdcque.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtcbnpyyqk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtghjyrarm.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtcwgmiegt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtzszwdagg.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtzgagrzob.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtchrrprra.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtdbtmwleb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtldalcwjw.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtinyxcnwd.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtrvpwpqrl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtdafmyyvc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdiherwa.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtbuurqfjn.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtkkxymwff.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtmgdbfloc.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtvxiybibt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtbwfrjwhr.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtzcpcgpyg.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtmdzdyvgm.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtrknuqwed.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgulczwx.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtkhbdamiv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gthadtbiya.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtrhggxdsj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtnkvlkkva.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtbxbixzop.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtyckaclqm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtephgrjza.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gthviqromv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtkbaoslsx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtfvxjpbqd.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtsjzgdvfv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtlbfytmeg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtxmhhxvuj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtoyhgchep.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtueqporny.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtsuegypnm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gttgmokxdb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtpttufcjk.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gteoeasqck.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtrotknnpd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtbxnwixzj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtlxmfpyyt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtzwvwwevx.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtqcgqmyef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtqyubguni.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtovqhhvij.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunmgccho.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gtqbtnejka.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtynoifcwb.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtlkbeorkl.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtqqaogxbg.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gttwxtogxs.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtzcgabrve.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtpjdvlwqo.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gthxovwaox.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gthazgqqmu.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtsuahryes.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtgdayyveb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvkbujhc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtcqafamgn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtajyxlyxa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtshrufcpt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtddswjlpf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtrmpcrgjs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtptqruvzc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtjttgcpow.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtfnrdqnof.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtdarmnniu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtmhvqgzar.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtebpzimmn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjifnnkx.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gteqrkcxoe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gttqephgha.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtcbkydpbt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtylmrkvby.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtabrpvgpq.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtdbhsgpia.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtybvdmrrv.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtodkqynax.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqgnnvxxp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtonnuzxuc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtdyvxwlnx.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gthgytdfdk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtmvpvvddl.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtjwzggtvo.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtlzjtodak.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtiuucwqki.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtttahhmzt.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvffwikfd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtydfnpary.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukqenvby.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtamrwigqt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtjyghjzcz.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtecqlonzi.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtalqskadu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtrewsaqrh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtksavxfie.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gttalhskwg.html


<!-- 参考信息 -->