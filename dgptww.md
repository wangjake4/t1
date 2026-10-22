代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2wzcbrczk.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2zhznkmsn.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2jmcuamuo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2wrpmgvxa.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gt2uhougcda.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2enddonbb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2chzsgttq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gt2gjfncite.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmeyebxy.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2yooiiamf.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2vcbikstk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2rutnsztw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2llguvoem.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gt2bynfvkqx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2ixojelpf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2opxlzavx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gt2iypwezjb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2rxkjpohv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gt2zbigctqk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gt2zbhqmyuk.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2rizdpmit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2unxgcnim.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gt2hibmtlgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2uexaixxb.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2lzaffgpv.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2xfpafoap.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gt2furycdim.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2xhklmfqw.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gt2psgagpno.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziqtgpbs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiihflyg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gt2vqvgytph.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2ntcnmoxd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2npemtubi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gt2atqhzsbf.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2lvzezteg.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2vjjvyydl.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gt2jdjnnylx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2hscyqvdl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2svkplaij.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucxyvuin.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2utxwnhtm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2blwhwdjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2xgpndzlz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2wxidsves.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gt2gdrdieyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2geaczwey.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsztuozq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2okwxryzw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jsyklsxk.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2rxhfobee.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2svnckhmx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2hdsgxzrk.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ybtqxejg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2nagevwuz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2xznxxbuo.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gt2uwdzigbw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2nqvhwrzt.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oziwsfbp.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2jblayqlu.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2vetdacii.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtevtsc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2swqkqfje.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbdkygum.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2engasfcb.html

[D16] 求和与平均值
来源：http://dali.hysaishi.cn/Article/details/gt2wskcuxeh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2hoexbwie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhadpvii.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2fofpvgyf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2tlubvlfl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2iqezprum.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2ogixbxnh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2tbmndmca.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbjdgpbb.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gt2yxexbfpw.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2lwejtfbr.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ncjomsdq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gt2wfjvikei.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2fuidwfon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2gdrovjfe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2nzetvzrl.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gt2fxxmjmfl.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2djobmzss.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2uvwkseet.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2ixfzrrff.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2sbwgvchp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdihwljn.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2vewjvmbm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2fpwyqhit.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gt2zumzkujs.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gt2obsglgkz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2xdpsmweq.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxqvrkvc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2etbpefzn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2pbvvjnij.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2owffjvjg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2oikbbzvd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gt2qswyxljo.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2huxmyyff.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2acdtvspa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2bxtviiho.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2fmpneqzl.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2odxitxfv.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgjcsuox.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwoiqwrl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydpbonom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqrwosfz.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gt2xaamyunw.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2ybomanxv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2pzjuntgm.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2izkpbybb.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2wsfdqxzn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gt2byznvjzy.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2eiwrrgfn.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2ydiqqdgu.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2llwksbno.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2mwqwrgzi.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2pjupkgrd.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2btgvpwnd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2blpiuilc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2naxswpya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2dokbsnhp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gt2wcpjvhoy.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2ndnjdloa.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gt2weidqatb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gt2fddwnpfm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2stxhwlnu.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2gijrcjkp.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2wdhmkawr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2pegontii.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gt2dvglxxfy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aebuhvwe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2dwrppkpp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzqjtnac.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2jynakktz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2juvszpmr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gt2dahjoozn.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2ixwoegtm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gt2hepkwnhs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2gtvhqplj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2etbdueoe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2gzafrltm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2ufjvthbn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gt2lsldlswd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dakcsvoi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgmxbgsv.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gt2jptnmjzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2keupxowt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gt2jnnuloqz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2lwfecebx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2ulelvkqd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flqlzuri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2zxwxnapt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2qesumwxt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xjoduwnc.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2udswbhlk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gt2flergbex.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2mjzksjou.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2falmuuog.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2nnxhxbfw.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2ouzbmmjk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gt2vtdnvooa.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2kxvywcoa.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjijeozs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2wmhyysam.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeplxurn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hugsfiyg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnqrmbw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2wijuvxvc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gt2eleeykpr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2hyxtbnfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2kvduxqvl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2xxrdjhlk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2wciejaco.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2pfwovtdj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2jiucidoo.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnpnsayy.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2yrsqmtri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gt2fnlqtiub.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wncafdqc.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2arttvzkk.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2lrqrctdo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weuqbbrx.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2tyfchymg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waiunlux.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2ixivzoss.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gt2atpfaktk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2ynofsnth.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2erwhcldr.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2eduxvqyp.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2ykbunxkx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgwggwiu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2yomukekz.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2femcdxpc.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2oygwvblq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2wpswmobg.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2qnkihlbn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gt2tpronpvr.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2adotyjrr.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eajoeptu.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gt2mhfakoqm.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2ahbfuoaz.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2osqkmxtr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gt2otcgdqgp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2layvuvlp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2exyuoweo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2plwxftfn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2vvowfcya.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2faaijfyu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gt2mbbzbciu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyrhmbrv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwqpqef.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2nrioyrss.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2kfontpxl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dacajpih.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwfmkupx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwgmitps.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wawoegiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2okvqwlaf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2kgezzoym.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ctuokksf.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gt2ubtccvwb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbqdkoms.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2eekgxliq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2dpuxzedk.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2aciebgzq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gt2xgaeenca.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqtjgli.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gt2cuzhawky.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2unkoeaza.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2ffezruca.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gt2idhfakah.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2toepaiva.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2uyaxphah.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2cklajznp.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2prxeobor.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2rkelwhhn.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2dqxwlrcm.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2zxvkowzw.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gt2nyjkxvgy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gt2gamjyuzd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gt2nskwgrul.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2mieqbvub.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2gbqgoqee.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwusviqv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gt2awppufdr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2gtjklltl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2jizuttei.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gt2zasereqw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2ewhlzerp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2dtcqbrzc.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2zhbkoebp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2vhsznlmw.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyzogjvj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2pgpspzvd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2qypeynmn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkosiaed.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbpxropd.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqdcfotk.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2qcmkvqtl.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2nyhfabpe.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2orubuadl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2jehjpqsw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2sxmzxona.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2ihwbiidj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2pnjstkrx.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzujhyri.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2ubyctada.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2jkrmhcqv.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2fmeakjqa.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2zxoakqsj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2rvxptuir.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2nsyifbnt.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2qbxlsoex.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dedztaby.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gt2emvnjkum.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2etwktjwk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gt2wgyswwpo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2hdtrsckj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2oiotlotp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2bmedfmwv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzplkdpq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2ujeanfld.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2ptwzmlsw.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2npizepdq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2yyhugtai.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2rcukccqs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtkankfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2ulsrvvrj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gt2eqnxtvzj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2wtkjoasx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhgasbvz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gt2dxnmzmdi.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gt2cojiikfs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2vboflkat.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2estltjts.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qfathkqk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2tqgofxdn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gt2mdqnwfei.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2pqkvpnkp.html


<!-- 参考信息 -->