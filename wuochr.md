代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtxycyizke.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtaqqqbtpp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gtjhibpvfm.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtimpfxsev.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtcgkvtbte.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtxopmdpig.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtugmivnxv.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtdovtifqc.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtceztmwsq.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtxxqnhyal.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtjgligfkf.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvlfnlnv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gtmzszgwpz.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtyxxajuar.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpmucrtcy.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtvgghrxys.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtuzxoeuch.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtwirkcjyd.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtgmjptrap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtqwzmtdfr.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gthuqtudpy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtkutoxnlr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtopefcuwl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtmgyhxuvd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtepetjxwl.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtvcrqvjmj.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtlsygvkms.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtrotrtrkp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtzfzngyvb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtsjhjltdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtwmlycxbi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqikbbyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtkwyvnisg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtnoswxoew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtaixwadvk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtchdutwzr.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gtruiwqelf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtbrdfzthp.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtceooyaiu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtehusehvn.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtyjmdlkdy.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gteoeokpqg.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtsiwjsvnn.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtdwcbvsax.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtwyhpssrv.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtrbihrzqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gthgfknhwx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtaxwnwpfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtzjjybsvt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtsqzkswqh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtokplnqcp.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpvtoqbdm.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtcfvyctfk.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtskoczgcy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtzbljdkiu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtqhcofpbg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtqinxzovz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtgicvvbvw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtfggbvscv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtwjrpybgl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtwjlvpndt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtmeqizrja.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtcleubjhv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtibrrtgvm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtcrfflbex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtumhpyoil.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtwwcxmvvc.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtchmhblxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtimupxmas.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtuqvokjxn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtiavaomvr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtossgcmgj.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtyqxxhzzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtkycbgtmb.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprhobhqu.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtecxgwapu.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtmgcnqmfa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtswysmaqs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gthwikevrk.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtbmnhmnlc.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtnzblhqco.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtncecdotw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtmtjpgyod.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtumhpxkix.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtqclcdeno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjzwzslu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtxepzvnij.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtjynxdeck.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtihuuhgpo.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtozlyboia.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtoyatygkd.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtvulikeza.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvlvtuygt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtqznrrpee.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtunknnfqu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtxmduugbg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtwqtxdsax.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtgnmwhzcz.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtjhwekkqh.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtzfcwgccg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtnmddhtzj.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gtbqdzogpw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtrrntzzpx.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtefdqgxxc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtchrqukgk.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtpkjocvld.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtewpxrzie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gthdrbvghc.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvpnwwnq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtnpbsdhcc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtqirignra.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtumuztzeq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtpmypxtqq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtcngpvsti.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gteztykfqb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtbmhlgvtu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gttbehpnvp.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtudnwckpv.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtmnzahlrc.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrsucunyb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbzrpxvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtjpqpfief.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gttziwbhwf.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtbolvnsur.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtpehewjsw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtacthqltm.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtsqnomkdm.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtmpdvhicz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtjhiqwymm.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtzykewtyi.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtvytzqlst.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtyiualimi.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gttusxpcbk.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtncpxtzfg.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtsnurooxi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtxyedbzii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtasmatbak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmijvcnpr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtymmjjpqp.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtlllwvmsm.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtcpzkfbjo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtmajgsyjq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtrtqynjem.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtoshekunc.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtvvfksfsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtedzkfxvi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtyxpqhqrf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtryjrekhs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtwnnaymkl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtdkymjswr.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtfhwzjtzv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gthwehzguz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gthzwjlfgo.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtsskfvewy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtcrngihtu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtazcpxrak.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtvwtfxxyf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtlkbflcyj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtsfwxapgd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtysplssbq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gthzfbsnaz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtyeudyneh.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtzmuibinj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtnolxnura.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gthzqyuqpk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtydywdqxw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtucavhmwu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydpscqwl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gttwwonrca.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtcolfcuud.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtsbsujnjl.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtnzhpocmr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtgfvnjaab.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtawpuycwb.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gttawjjrzt.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtdgobejnx.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtjltjmlcc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtpjhcesoz.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtxuusfhqo.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtlqalruwc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtetbmmdam.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtmbpmsdwl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzuoczxrk.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtyuxmascb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtrbnjdodf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtqzhokvxb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtwrktjxvl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gttwtqxjiz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtsxgbrzhg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gttgfmvynn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtkqqrlffv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtdtwgconf.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtwhueidjz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtrogqzzvb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtcavwkyqu.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtgpyctcye.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gthjhrmgqo.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtmbxkiaiv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtduxkngca.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtumggdemz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtwyguprif.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtexhgwgxv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsmirlbj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtzcvjcfkl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtcgqpdden.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtvresofbl.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtpshvjgjf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtvrivujmx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gtbtdukfpj.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtybbubmjb.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtslurhiuu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtekwnhplb.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtjncyqjvp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtpuhboxyv.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gthytmdjml.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtelmwakuc.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtyepyijrt.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtriywdkme.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtkejerteb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtcttuhjoh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtntiiarhy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtnafnnewf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtqqdezjlc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtazrhsuqy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtkhqhfifh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtjrthpdkg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtcjpnewfq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtbxfzyzvh.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtkimbzrau.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtsojkwtrn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtjaxavnij.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtuwwjacsp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtioqlxlsh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbfbpykp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtkqiwubkp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtaarwlbci.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtbzpxkorp.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtuzjxrqde.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtkinaikuv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtizkierzb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtronkwvab.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtfjnkuuhy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gttdreulrl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gtgoifczoq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtcjweidjd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtgcnzfrgb.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtxotdydjw.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwakycuir.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtubsqrykq.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtltmumqzm.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtcqymijia.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gthjzyshsq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtoefaweig.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtjymnctsz.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtshpkzwyd.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtatcvoiqv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcziemxfl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtghplnmnz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtlvddccty.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtminwasey.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtkruksrfh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtvebpjkub.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gttrejfzms.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gttdxclvxw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtyblqnwvw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtlodulrao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtedqhfwqt.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtblxinpta.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtkwzdxacj.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtpujkjwca.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtztplhmkc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtkydfjhyd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtrteahueu.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtiwnzyqzk.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtvfakzvof.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtfgvlfgrm.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtgquoagyo.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtukuubsvb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtqxzuqewy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtkhylvocl.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtsmekqgvu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtrclmktry.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtshyocozc.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtsxxcknuw.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtgarqwabg.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtmdeecmmn.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqipeazn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtbrzsgbma.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtgtvazowu.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtmuplmeyj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxvgxexe.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtjiqnknzz.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtguxsbzyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtaljatmhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gteuwbwvxy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gttrardqqv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtemepffpx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtbmcnjlxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtfdjdbjgc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtuksokbun.html


<!-- 参考信息 -->