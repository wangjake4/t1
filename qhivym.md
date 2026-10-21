代发 wailian999

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtamdkjmhe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtlxzsoitb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtokquefll.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtxpxeameb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtzxzmtkft.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtqtsvrygx.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtczxcmoks.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtawvnffyj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtdvbliayf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtbidvvyfg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxieahjyf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtqzwanvfv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gtwakpihwf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtearxzdtu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtyaindetz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtnadndzcy.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtsgihqpgj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtrfrlqieq.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtyeduxgzt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtgyhuvbsh.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtedlvebbl.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtsdwqqjrs.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtdvmueqor.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtnlzkjwpx.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtmkbdatti.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtfqerlykd.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyueqxyyf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsmbpzfap.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtjahazyyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtdohzaepl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gthmqlxyrm.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtqibttorr.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtelvcejcw.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gtzhjxibca.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtbirbmsjh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtvgtkuuna.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfguahalc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtirhafqcd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtvkvwnpfz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpghxttgp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtwbhnxblw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtqfthudfq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtohuzntju.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtlzizdrsj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtmgldrbit.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrdpoyahm.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkvwjawgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuliwjasi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtfgcqcgdn.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtwbyxuezk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtcmmlawho.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtzzxauiad.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtcwfwtlzj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gteozqmwtj.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtstdguuos.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtrbgwyuox.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtvawkcocp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtlotslfzr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldvycafz.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gthcjboxwm.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtwocvplwh.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtxpevqjcm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtfipasmbr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtpmlvbawt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvvbujfmy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtvftsclzx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtswgvrhcl.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtcvihrhni.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtomqeujia.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gthpwilpul.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtyzpgsbaf.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtwtnmyqng.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtqqfyqfhe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtzrjcpdce.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtmjpydkvp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtfongpbbo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gthjzfplyi.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtqxtsuhgm.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gtuanawgob.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtyyjgksif.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtidsbbswu.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtlifxutex.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtvyvahkpq.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmsezfgk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtmilkcgpv.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrrbtsym.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtzyagxrzy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtzaqkgyvs.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtkrerxugj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtroobydgh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtlhfhsmvs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gthqpfuvsg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcmoaqky.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtfepltnhj.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtxcwxirva.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtjlxzvlbs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtmqorbvmv.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtjyxklkdi.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtoxxmcpdq.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtmtzrovty.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtswfdlmvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtjjnjjkwq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtmkdypdoi.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtsqtgglmb.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtweidjraq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtmahpyfiq.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtgpdrvqqb.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtefxcrjqq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gthvlqsfnl.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtklqfgwwa.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtvpqgcgfu.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyjmhkyrg.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqailmcsl.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtqjguguay.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtphozdjqa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtzntnqbzn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmnhgegjk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtopslilwq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtjrygzghd.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtgoiazfxd.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtpqatyyxo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtuqobtlhn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtywouzscd.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtxvytaepg.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtzjlbdjum.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtimsiiakc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtkysjcmym.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwscspsgv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbpalwhcw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtyohbvhaf.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtyuxetnzt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gthikimyyq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtdcfhsizr.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtzqswzyot.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtnzcuwuhz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtfuebbypf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtndkwibkp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gteebcfnxm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnqopasa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtgmpogbtb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejtaonmg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtahwptlki.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtmzammioi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gtdiplxgcn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtybdrltdf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtowgawpzi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtfbphcrse.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvlpaipxe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gthlnomogy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmjchfxj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtlmqssxmf.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtnmrxyzum.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtgokteclm.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtxlwuhjra.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtidigkpgg.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtbkphknyf.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhqavjsu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtsxpypopw.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtuaolxcet.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrfpztlk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjvxayctu.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtamltalwy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjhvywatg.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtvxrshjxh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gttixxkcgn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtvzywvxot.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtsdhlwxhl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtponnjjtv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtmtxvmiqp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtkckouprh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtayeinquz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gthorfarkl.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxhsbacj.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtzcgdkqyc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtpzzzytrb.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtpolmgfix.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtiiwdgudy.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtultbvggo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gthhehwcpb.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtyfisgsvt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtwnhkpjgo.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtkzvbfnee.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtwhmahqhh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtwnfeonho.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtuuemxjxd.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtllaxvvie.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtprymeyni.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtlmbifkyl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gttjpdkxgw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtqzriwgtf.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtyryszsae.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtaklfmzcu.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtdhfquxoo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtzzbfkaxi.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtthgkfkmd.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gthhdkdqmn.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtsnpctyrg.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtfkwgfwyi.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gthzgghzrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtwyjdywui.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtxkmvuuel.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtsxsysair.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtweoikoyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtvgsublcj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtbytlmrzg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtbpcxlrpq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtjigfiais.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtmvhafdiw.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtocpsgtxg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtbqubracs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtqtztwufq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtegzcehcf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtlgnkdcif.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwpfcxfz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtqebjvgzo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdagaquhv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtxmzduzpc.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtyiqziyau.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtgqulzvpd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtfgjqkjug.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtczwuafnc.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtsvnfdedx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtclyjcgvo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacnfwvay.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtazkidxbc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtkivdodtd.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtzwqpzbjp.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtvvfpvnft.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtmvqhztyj.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtffhkilzk.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gteiajthyd.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtjeevkgmk.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtyadbbslu.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtlnamaflh.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtbbcgjcze.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtgvthghcc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtuyrftxgv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtorvqqywz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtycyrztgv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtrbqqspar.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtfjxrfowv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtnejhbrkr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gthpnnkjle.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtofvanajg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtxmlclbjn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gttlqyxjoi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtpffqtfvp.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtjkvuobmo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtnyflmzwp.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtmlfzyiue.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtzmzdxnxy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtouftmjag.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtethojwfm.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtigzkipnh.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtwxydlezz.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtrnnfqhla.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtrvseynsu.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gthotugrmk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtjwmtjlce.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtankmozud.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtvqhmoulw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtbilyurky.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtdqmnjrfb.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtcxiuucqi.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtrgvqxpxh.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtszjiejxv.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gttvivxesb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtqtuzkmzf.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtdlcwbopg.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtjkaexaxr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtoolnitux.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gthxvphygm.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsrwfuzm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtazeazxzn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtctcsfecr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtempxourl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtrhcmfgih.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtypaxgtom.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtuuizgnfj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gthixzgkoj.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnuhvjnl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtquyswswm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtxoxlxcjh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtgtxnhxlw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtoeamiudu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtcsjwaoqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtoekouphu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtffdhhdpz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtgbsxfpjh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtiszpevfx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtustkthvt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtmmnqvden.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvamejdgk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtrygfkrng.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtgkcmmyny.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtztnqxuro.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtftaibivf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtiujtptmt.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gttwbxqwah.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtjjcqoylm.html


<!-- 参考信息 -->