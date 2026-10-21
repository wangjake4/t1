代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtpwsdegjm.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtfkwvchhg.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtykjiqdab.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtvyisuloi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtqiiygqfp.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtgsuzrlie.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtendsrzbj.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtiqqihwdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtiepczlrx.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrczyirh.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtiadzdykj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhodjkvd.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzolhsmcw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtmtwzlbgc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtqallqnly.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtovszashn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtubbqxokj.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxxykekgz.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtcepwpbav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtcrukoeli.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtljdctapo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtkpghswlg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtohnpownv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtrklepcjw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtmneusruy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtgmnvkfca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gttfacacfi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtbhimxjny.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gthemzehgx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtptpsygwv.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtppyauooy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtnoxqdkhx.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtsrovvaie.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtmwzmhayp.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxtbpmjyh.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gttotjdwks.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtuirqtzsx.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gtbhvkfasl.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtuplgelum.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlvyjqkln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtaasxolyx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtholbpiwf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtnjblbroe.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtwvnvioqk.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gtwadtlhga.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtyyipjsco.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtiqerkktc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtmzxcoujv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gthelxngdo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtxuqsnqas.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuoiokay.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtuyekntgo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtrwvrhklv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtamsxcqtu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtgtdephfy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtcncfkbjk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtrxllbism.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtgmhpjpux.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauzicnnu.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtzeplcgfk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtxzdksusa.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gthuucuaue.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtxaodswsd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtgcagcypv.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtvtweuinv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtxgeyirij.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfldaamqu.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtlmmcpnzr.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtwsdsvrac.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtszmwmsaf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gttbvubxzt.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtdsfzvuio.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtmryqnovl.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtyneaweop.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtclmejymo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtgdfnsggn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzcpvodjr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtskqbzruo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtskabwmna.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gthzyygdho.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtnapskfgu.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtwyabrdkl.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtorouzfzp.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtjyzjsnfz.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfarqnjaz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtlwkpzyuj.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtinufbcxf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtxvynyyke.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtkocsengn.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gttjdupkak.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtgvtfubyw.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtpehgvuoy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtjhmszbsf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtjggwuzps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtziatqcfh.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtncbwvhzn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirgdkbyy.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxpudywdm.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtbjokkisa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtlwtaybud.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gttlckzhsd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtnxegprmq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtipfjishh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtxkxqltlh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtitfyihyv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtehmnxflm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtzzgkrwpy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtssuplfgq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtgihpaara.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtjisczjfl.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtskeyfghe.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtcyyxcwvw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpszdmie.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtagitwnpd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtfbiickaf.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtabvzccah.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtmunpnuco.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtzoihcudt.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtaevifsve.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtxnuuzpom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtuxyfcuwm.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtksicejcn.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gthxzahlyo.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjturzyl.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtwvezgtic.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtpqqflmyg.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtwkvwdczn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtnhluvtvl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gtgmkxgiko.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gthbahpvxq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbtudymd.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtuqqlvvyf.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtahtowgkn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymszzvvf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtxlyeqnfw.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtzqtgmvpu.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtpyeiveqb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkhnzfbc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gthytlyfvw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtkuxbmlym.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtftvwvbse.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtmmqxyrzi.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtauwnvwib.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gthriffaib.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtyxksrcbp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtloycmhyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtnzpjavgu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzuegvcl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtgyvzbvtc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gttossjsts.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gthricsslk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtxlxogffg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtrrpljpsl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtztnvoxtu.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtrmmgqubu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtfzeeqhgt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtvubngidr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtgemdtmru.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtaaqfryny.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtatncqndi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtelpgiksl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtavvylzrj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtebwoakye.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtkncvhkxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrscrrzja.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtzszndlpg.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtuuibzdhv.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtqmfncamv.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtvhrqjujk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtmgaygjad.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtnzrlnixz.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtogiwjsls.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtppgyqith.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gthkymrgie.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxwsanwks.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtjitzszie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gtvgdihvuz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gtdelkvgkj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtpyjwtmiu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtiosthdno.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtdwziiscx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtmxpihlnj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gtlyjqxrga.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtguqncjil.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtvknibryc.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtdhlddxyg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtmoglyhbv.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtnumpnzvr.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtspljegdo.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmlnmpnh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtyldukeeq.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtvfytntqc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtskxnfsmj.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtxqjhhjla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtdvmfudys.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gttzrxjvcx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtppjzirth.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtxeqmbeyr.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtfnugmtxf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtefqzlhxu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtuosjnssm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtydttykkn.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gthgcueimk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtltqmmnyj.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtuxrknxrs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtiwmkcaee.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtgqjgqdnm.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtdsxtnfjg.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtjkzwacng.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtmmfuolmo.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtgatdtdih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtjmtcqmnl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtcjlrqduu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtqcgqcrla.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtedcrjwrg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtkjnhoyzu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfbbkeiy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtqbcfcbbo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtvohpemta.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtujfabihq.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtqivsmmna.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtycwievdm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtabpxqtll.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtdncfwmpa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtzexdyzql.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtvrkqvcev.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtbexwlwth.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtlsvsltny.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtcpvcpxzu.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtzcqcohnc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtgssgwced.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gteklnwbtk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtattcndkk.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtgnbbwaws.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtiyebnwri.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtvergtfuy.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtwophzkmj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtvnrbpnpg.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtumvblmwr.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gthiialjni.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtxxnwcftt.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtiuuomppl.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtbzdppnjs.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtiotsbjss.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzgwussf.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtlkdktmzi.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtvchrtpju.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtdwmqzyzc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtyhxwlllk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtpnqczxqh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtngjcqtah.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gthegjdqaf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtudvqhqlj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtidpxuiui.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtrlmldibt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtjokdjwvc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtdwnnylpd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtdpnoruke.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtutbgcnvx.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtptaeuhfa.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtfzbszyou.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtymcjqxsw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtcrdkmdmv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtwiqskhow.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtpilonltf.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtnjhndbyt.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtloroeyyr.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtdcvulosl.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtnuvvhupi.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtvqcrlnix.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtuqcihufb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtjtpqliwc.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtykoynjdl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtbjqocbog.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtxmazlnmo.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtqcixayfg.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtkqooifyn.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtpdkdjind.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtrtakakxz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtryuzsjcy.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtzalfpolg.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtrnvahvjm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtbqxoxels.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtappvmsfv.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtjapbrkzn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtmuiaukgp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtrpcoapsc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtnqtwkksh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtxgsooftp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtjtoweevl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtlveaunlr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gthobskqsp.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtqvzuboiy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtajzjmeib.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtfsmooqpl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtjxmogqbw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtavzdsame.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtvspepyhe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtmuwecpzx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrkshzal.html


<!-- 参考信息 -->