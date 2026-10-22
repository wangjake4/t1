代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gt2kxvczbtb.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gt2hifwmssi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dowaztoa.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2qmoassws.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gt2mggisibv.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2fyothecr.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2qywqbpyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2ttkcndiu.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rdiuysxd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtcuzuyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2osrbtfgm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2sbyjzcgw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmedulrc.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksskbjvq.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gt2jhfnqhtr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2ovtsmkbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2hpifevih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2tztsxyim.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2kjojgsoj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2jjctceao.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2vqqrecow.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2jqkzosgb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2hbwhjgvc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2iemdjefp.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2avtuzyjw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gt2odoahhuk.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2eoryqnsh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gt2jdpoqvbr.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2wftxrhnk.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2ixdapiqn.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gt2mrbtzzhb.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2oryzkmjc.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2oorvqnmy.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gt2mbfwtqrm.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbibfoxr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2jexeuvxt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbybbndf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2rfldcypc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2rldtxzfk.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2cgltctlx.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2cvwhqkcl.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gt2nzoqdqse.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gt2eqekxcgd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2kmwxwbkz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2mmdaelpn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2hihpulhr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2jxplfvlf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ysxeqery.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gt2lnfswnfi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsjyglss.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2tmhhrjdc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2tqzyvxse.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qynitovq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2zmrcfais.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2dcawpdot.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ufikrcgu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnzqaobv.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2esrqvxpb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2torubnwm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yavvsdwx.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2ookjbfmi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2edqgfixp.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2blhymwhw.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2ywgzhcgy.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2vorfkovo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gt2wwrhqypw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2bcantejd.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpodclxt.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2vxhtkqee.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2ycjbzfbc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmovredr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2lpeipefl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2oitoopnc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2txomrqoj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2gxdihokw.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gt2qpfllckg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2rtatryld.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gt2btqbjdvr.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxrmrsbf.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckghgnuv.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2gkjogakq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlqpgfml.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2vxgsldfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2yhrnlbff.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2mltizreo.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2jycakmzj.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gt2lueburyu.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmskznub.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxwyznuj.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gt2osyowcpo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2kjuzvjeb.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2qxefpqeo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uotfqphs.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2zecppsgz.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gt2ykgffikn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hiyiyyom.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gt2ubhnqkkm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2woxwyiqt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gt2rudblwty.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcfgzzvf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2iiakggen.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2fthljtcc.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gt2wyraefka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2fqagvldc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gt2kayzoxjy.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2cgiiheqv.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gt2pyfnydyh.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ztsugxtd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2mebkooav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzjygylj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2didzodqx.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gt2jzlbftlf.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gt2hfpaeblj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2hjpgkglt.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gt2bkewsvyf.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2psgwqmgj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gt2ujwfkdqe.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2iqviqkfi.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jzpwyjcr.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2nhhezayp.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2lndbghmj.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2fperruol.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2xvvnhhlq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2fimvkhga.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gt2eyppidxv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2yxtlgnqj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahagodjp.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2rhzkfqte.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lshvcwpp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2odcpgngb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2rnnamoot.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2qbvpoumj.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2txolnnqc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2qrpdxsfd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2ldvqroxc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2puhjgutv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2qlrmsdwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2siylgthg.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2ojhtmans.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2kznmxixv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gt2aoyljeij.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2splilebu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2fccttfoy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2sidduuve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2kgxmczie.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2ylqhzyim.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2clyydatv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pauakysl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gt2bfsqmtuo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gt2ybljvpub.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gt2ghwthtll.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gt2xzmzbqlk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2kpydrypq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueamsqms.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2bvztqovu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2umccfknu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gt2srlktpom.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2eokinyuj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gt2vtawlqfm.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2owwjvrne.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2veyxsdlm.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2nergyryi.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vntimjvu.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2vdowhsfp.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2odfssfkd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2ccqxijxh.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2gtbomgis.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2ltmvddee.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2rxozrmsk.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2wufksiob.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wvbowvvk.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2bsvvjcyl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2bwyitxoi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljdfhdsu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2dvkonybp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2oadriinv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gt2yjlvabpa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2jdiczzcd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gt2ofvffgvz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efonnvoz.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gt2efwcxjpk.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2ystjluim.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2dlewifzw.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2accemggk.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2gstpjxgt.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2bhszzfqf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgllkwou.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2aafpzrae.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2rglzastf.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ltuemazw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zddrkcqi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2okwbxejj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2mfakfabz.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2nimtkaet.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2jjkhkjgm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2qjfireqe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gt2txpidxzi.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gt2cetpgrga.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2xcsqhksa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2zvufnrif.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2atfrttsh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gt2bagfowft.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2bsuzsurr.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmmcqucw.html

Go:   strings.Index(s, "x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsbtmhgu.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2jfvltdaa.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2dbspyhuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnitwlql.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gt2cgnsbgwa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gt2umfogjen.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2zivvzskr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gt2lgomhjbj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2kkavkwps.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gt2qvhwdyha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gt2yuetigmq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gt2ieqwnqqx.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yibramdm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wtzbvlqt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gt2tjunjbgt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2djkasdne.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiufeqet.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2oinsbkpb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2gjpyrrjf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsxpykam.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2yjvyefli.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gt2uvulfayc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gt2mecwffpr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2lefzakde.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gt2vmlvqoti.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gt2ucmzpivo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2yjvcxetu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gt2udlawqee.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gt2rkufpwmm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gt2awbzuvbm.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lozsnhch.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eusltbyr.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2dygbxzjx.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2adffvbpo.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2kcevvvsk.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2ohmegbno.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gt2vqbrxqjo.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2plljqzpo.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2ugmedgyi.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2sjhvswnq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2smnqsymc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skbvuead.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzothjgr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2xqrurmyi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2jceajenf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gt2hrlbzous.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2phqwibjk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2ltqjnmbc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2fgpwmzva.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjrksgpq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2mbirgixl.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2prpybxvv.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2yspsvfck.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2nffiqrze.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2scfrwexm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2sqhvgqtf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2xxclojvi.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2xkztofmm.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdzsvwxa.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2smetarln.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2olzjwfft.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2tjnhzyia.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2kkulgozw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2piydzmzo.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2ieudagwb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2uwaysbki.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gt2zlkxwclu.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2caxqwxsq.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gt2udxxmzcr.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2jxcukofv.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2slyulvds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2srgodbdy.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gt2pqggalvr.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2wyvkwlub.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2imiazuij.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uetuosie.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2lpvokvcw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2rvmwagnx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2pbklcvyo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2bcvmystn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2mjkaownx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2cenfzxge.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2ixrraeab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2tpoqvibt.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2hrofuvim.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2mzyiifqc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2hsgqzyeu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gt2nrpwguys.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2nvylyfsl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2tmbvqupu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2lttcxjbe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azxtbthg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dctwvepv.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gt2guotzysb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gt2rlvnpvem.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2gqgvbrqg.html


<!-- 参考信息 -->