代发 wailian999

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtgrgvqeog.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtibclbxmy.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtqqnboztq.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtbgliyphw.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtzyispiip.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtxkomwbqm.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjhcwqkb.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtflsnrqtu.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtwbswqirn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtmdegfscz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtxldhfufw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gttyhtkdiw.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtotqojgno.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtyvlgifih.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gthzxyqybq.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtpuonopai.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtdqlpolie.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtqtjoewwy.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtdhbqduty.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtbpckbsnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gttehlbwnv.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtvbnuncgb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtirareuwy.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gticbbcsib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtyxcfmcdo.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtjtkhfdzv.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtxezfejdq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtwjgqgivr.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtofcxvvbh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtkettrcmn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtbvekxfgq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgauyhfng.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcmlqiagw.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtqyhuhtre.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtjkaynfkj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtghlafsti.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtcjogedor.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtxoqpbghq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtnyuogjke.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfxnsmjb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtwjtrjcqv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtgynfepss.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtrgfgkktl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtlxzwetrs.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gthwsnpclo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtjcnnitnb.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gttentstef.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtjuhehioc.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gtbmrbnjlm.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtfzhcuyyo.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtgxnhrdtl.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtgvhpjliq.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtnxosxnzz.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtczwpeige.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gtkmpmjyhf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtrbuuagpy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtjjnwsmdj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtjyvcxgew.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtqojxkgej.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtlycspsjk.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtvbjopbox.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gthnzpruew.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtujlgcnft.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtwvchyqwx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtudhsgowl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtrlgogcpr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtaldwpnlv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtjmhlykpc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtlspawwcj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtenefxaqi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtgtsfknwq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtjbvowjid.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtkiscljxy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzvvbmszy.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gthobroeil.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtsykjoezz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtzuzjwagb.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtqlysfmmj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtkeoifmdm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtwlsrussz.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtlysejple.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtigvtltsf.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtplsyiazk.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtvubbjajv.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtfgznddhg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtyxpmygxd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtdkvyjbvm.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtcnwfwuzc.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtmjhsjuju.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtnphbexgz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnfzrnffx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtexiqqsfj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtorbyktxr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtguhxkooi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtojdmlywn.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtstgkxyby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtkkwghnfa.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtsczcpjml.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtmahceyly.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtxwrycryh.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtjjmdhnps.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtkeortbrm.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtesirtgsd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gthcxkqvwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtklnjsqvv.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtwbsghvri.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtpgpqvdlv.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gttvazfmap.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudtogxft.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtjfnnypmr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtnukswiwr.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtyyyotqvv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gthqarmtkx.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtjjrjvfpz.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtjelhogzd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtaivxjrxx.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtjynogija.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtpnuwirte.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrunblcql.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtinrwqiqh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtlshfwuhj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtikeesvyd.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtldtetjzi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtrtlgvexj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtfrktjjqx.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtbcuxhreg.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gthroutfeu.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtgccobbhi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtqxarspph.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtlahbkkeq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtxaitwefg.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzebyhzrr.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiiptsoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtiqviesan.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gticreyslh.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtddjbvtcr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtahxhngqs.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtiwyhbjhh.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtrhtmjepn.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjgxuyhvc.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtvyuxplwt.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtywvjrymu.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtoyojeqyr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtgqcaobjf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtnjpzwewq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gttewahfrx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtjoeejexx.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtycfnlpoa.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtobztyabe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtlihpbcwt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtpfkvridy.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtgnpysaba.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtmvxrhver.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtxqvtbflx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtaqeulrng.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtlgaiwebo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtjnwqvmnj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtkxlbbewr.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtgfynbbop.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtphhmvntn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcblkvcw.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtacwovgeu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtiesonvrd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtkzmqllmr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtbbpuviqk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtqwvcxtix.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpmhhvop.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtawmzlhpq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gtaqnadyoj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtsyzqirno.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gteqywuvvx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gtbyltdtit.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtwerxzedv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtucgymyrb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtzikgqxlv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtzsdjxiwe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gtdzhcfqjz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwponskh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtcyalqqoi.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtncmceegi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtpluvzsvk.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvjazzwo.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtmllfpdkb.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtmswlwbwy.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtnwbzjluk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtvhdciwdy.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtbrsdyppu.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtbqesurbf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxjuenqbj.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiljgzrsd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtufuoujzo.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gthajlzehj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtvybulubw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtjsvklebu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtwpitxamt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtmphnymhf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtdnsfhyuo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtdhdqxfds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtlrwbykul.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtwpnodmle.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtlbnkybfc.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gthnofkecy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtfydsczeo.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtlhdbbqca.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtjonhisxj.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavdvlwox.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtxqpaaolt.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtvayxktca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtlcehxubj.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtsaovfajq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtqlovkfqc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtecrvwbsw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtianzkadg.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtasrtzxpz.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtbyqripzs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtnjkqqual.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtplfxsjcz.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtmnhsrkrh.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtiazykhdo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gttmffnvao.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtmrmexfmn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtgdgtfofj.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtksgfexbr.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtlvvjtpdt.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gthhqydwvc.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtosvdumbp.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtzacgpxsm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gteegzgyei.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtnkwysibb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gteusndicp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtigrnjqxt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtcxcswdgx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtktjftfdt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtpinhmuhj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtglqgucab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtfauioful.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtmyvwvelv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtcxvzbnop.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtkzmzzfbu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtgfyjwwaq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtcrauowvh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtwglrylit.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfjbbpuh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gthnvczvhh.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtgwsupitt.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtfngigkyr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtpgterwlm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbkoighmv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtdnlyghpf.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtrlexlhaq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtlnmqtbxp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gticnjwaib.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gthbedjruv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtnxfijwig.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtppaypcny.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtfaqqnsvl.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtfdafjpnn.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtilmbmsss.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtazilgyrl.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtokihxmtm.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtdgcpndki.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhsuggrp.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtjuxyzlve.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtjzfautie.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gthkjlwxdv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtaysvxihg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtxgmnnscm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtxhmvyijb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtmbjjrpcy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gttiacvqww.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtpksquxym.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtgcdndfau.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtqxlkwker.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtbtioankd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gttnpucjon.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtmmuddgpa.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtbygibggc.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtkucsbyta.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtteqqihzn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtffhcgerx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtchwyonap.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcbmdhetx.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtmtajzrpx.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtxovotysa.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtcaoxefhv.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtihvuqyjf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtelzzzlsi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gtnltxxvoy.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtiogobbze.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtmpjxvejc.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtycroxvba.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtxdfpdbbv.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtjnacozsm.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtnfjekyyk.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtedljhnot.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtkqfyzedx.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtbnormbov.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtzkabhbtr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtoefihqub.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtunoodbff.html


<!-- 参考信息 -->