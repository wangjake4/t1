代发 wailian999

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtxwakcugf.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtjaeglqxv.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtdpjkkjnm.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtrjhlgbzr.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtndknuwnh.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtanupmpxb.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtokrurtaz.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtpkhhajsn.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gteinsgwxt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtcjhuqols.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtyxzmiicl.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtombdgqyj.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gttoulinpz.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtxpeudata.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtigemgfqp.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gthqdkepmu.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtyqyayxka.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtklqynmrp.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gttsdaxjsp.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gtiahnpzqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtmadpmtwp.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtcncyuoaq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtnkmnzqru.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtmlinoeky.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtthrgzzrv.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtpjhreruj.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtkfnhbdll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtlrkhuzcu.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvihoclps.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtlveindge.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtyfwlchwy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtmurpasnm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtzofepgfj.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkhewtwm.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtwvmrtrow.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gthuzotoxh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtrotyhlya.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gthagdfmki.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtwqcznwmx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gthvvrbcia.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtgpycriit.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtjupznojs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gtjgzthhyu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtfvngrvuk.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtfmkfwvwj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtkxyewbey.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtscagnpmx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtgejoufat.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtcpsqhuwl.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtdzmqgxoj.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gtdhekrjyy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtffkwhcdn.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtpepxcgax.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtsnpqfdgo.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtjvblzfsl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzobdaeb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtqithuyoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtccomrfyo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtdxvqrias.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfytztkiu.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtigxipivy.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtcesepttl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtwmrzvsww.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtahnkgprg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtdtqkhuxb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtstvixpst.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwarsidp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtlzdvqoqd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtotzdvbbh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtndrjuvar.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtzwibuydd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtxgqfzjzc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtkyzalgpq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtxhvspnyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtyvuthtso.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuoljmuew.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gtknvqghsg.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtndqseqsm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gthcwocjog.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtthgmrell.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdujbnsp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtkufiknnb.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtucjalskm.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtrbbkhukp.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtjsjsrjia.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtdphpcvku.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtktzcswau.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtfesvcnpq.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtifwsjisy.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtkdomokzt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtftdiuhri.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtbltzopdf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gthuuepcwg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtstvvihmc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtvjupjtds.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtvuuvicdo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtachritej.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gtsjuxipvb.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtgodhugze.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjijjchdz.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gthzfkelor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtwpnymlqc.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtnklvqpwl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheutgzkb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtglpewgps.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtolegkgrg.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtgdkwndec.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtehaxvqbg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtxonfjwoq.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtftruvhap.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtqrbarkst.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtpnztptod.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gteeerkggu.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtofnegmqb.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtrvutmxnb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthtgnsgdu.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtrntrmhac.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtpkhzyiot.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtngyqtyal.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtadkkpxxf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtowzidnhx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtszxsmrdf.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtvedrfebc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtptthedir.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtijyaqsaw.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtuhbjvigg.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtcbgbwivf.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtoquravor.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtybnjolin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtfkhrhitt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtqfjpbyui.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtfntguwmv.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtqssurriu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtkwerrqey.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtrdodwocb.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtqgykzgmh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtfmhlmrvf.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtpxurhblk.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtpdamqkwt.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtuffcoozj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gterqsehtm.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtysfpvsfd.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtdmbgoaoq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttktdkoch.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotodaptv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtbgloevsm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtyhatlqzr.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtktminiiw.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtvrkwqqkg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtxpezncar.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtkixtxags.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtndikymem.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtkqcgxodj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gticcylzof.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtdubvjiyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtijbstvth.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtwytlslws.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gthgkcouem.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtmjttfdaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtivachtjr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtmuwahqsm.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtmwhxyjox.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtrxripuws.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtqvdceswp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzbbpyjgx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtpkxwmtmd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtxfkefdiy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtqjwoeqkr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtmxsofbcb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrmgesxi.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtbshwgast.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtpgwoonyw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtzyiblkyc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtyhhogesc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtzuivuqjy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtqptgfawh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtymajnsoz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtkfaoghyx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gttxrwrgjd.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtzljnehnp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtdxmjxkqj.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtfvljzgoe.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtjwiecvks.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgprbiafy.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtvpkzjuot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtogfpcwsf.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtsjvwpiby.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtxziktzyi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtweugxoru.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtneboxzzl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttgxbgxcq.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtkbsgqxgi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gtwbwcpvrh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gticxnxzfb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gttxvzteaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtctwllfom.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkekwooy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvbjuanl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtgkiuqhib.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtyshtimaq.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuojbnicr.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtogcxuira.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtmnyozioo.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtbirutxkk.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtasgpfnrg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gticyofwzd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtiuomrgva.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolwscxkx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtrkotkmrq.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtsbdtccoh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtcjituczg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtbhysgjdi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtrnchhqcn.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwbyeuwjw.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmdkxibfs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtoethhbsy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtnqoknffg.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtblivnazj.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtyntembcg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtwwcapwzl.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkfpfjnh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtgsqvfmvr.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtshhcvjjd.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsltwfvv.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtrnkqxcwa.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtfphswkui.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtkzddfjkg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtfeottpyy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtolpxnezc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtfummfomt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtaopjqmwn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtwscjhaoz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtqcsjzket.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtnvpbgmkj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtqivzfbip.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcribkqu.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtasetknhh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtmkyxikrv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtsidrqffm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtcqqpdhje.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtagzhomkr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtmbcbrebo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtbwkhqjrs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtozzterzs.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtxecnuzbh.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtypjlpacj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtincdlawj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtqsdmemqq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtrmesxstu.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtcwdokkfo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtustpapgo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmudsmtxi.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtmplkdcrf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtnikrkzqg.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtaykpmfiu.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtrudlyqfm.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtkvmvyvas.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtqdklycvj.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtyipzmasz.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtgpqqyjtl.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtfmqyujww.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtewekkzux.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtuidofblw.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtgzfkdlyb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtxhuilsta.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsqjgqdxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtmnatnunq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtcsgwfjsu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtvehjjfnn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtfxoifphh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtjafyaqtt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtmrbmkkmm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtdkleyphk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjysvzvvl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gtdvdanrzr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gttusfiigj.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtovwvkhkb.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtrlhbknhr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtwikzxjdi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdnlycal.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtthrlvwvq.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtjbswbfpv.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtmtnhhkta.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtaotnfcev.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtxuubcwji.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtqlxqvmct.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtxshmuewh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gthhwfnxeq.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtfftefdtw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoavokxcz.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtuoqguaxg.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtgctcclcs.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeareodi.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtglaclebx.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtngjlitdz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbdcdijw.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtyxmbhmdr.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtqytwlruj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtzhockmib.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbstwjpe.html


<!-- 参考信息 -->