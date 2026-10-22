代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2gwgrgsgz.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2xktembvq.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2zzfscwpb.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2crqydbxt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2rcpzuevm.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smzaabgf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2phgiwmzz.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2lxqhtsph.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdyoedny.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2xxeerisw.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gt2olrzwjpd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2cehdfcod.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2nwipzjqt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2saonzonc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2vrcupegv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2jmelfzog.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2jaoebqxe.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2eqyxlpbk.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2izurzfgo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2ysjiacox.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2rncyyrdj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2bonaovoy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2iuuwbpmo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2ksvlfmkp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2zlndzxkp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2bzxhugcp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gt2uqtwcxcn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gt2nzmwzfsv.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2yzscrdpa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gt2nhqkjike.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2qfopelgy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2udyddyfs.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gt2ipntwnic.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2srzxqyku.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvpxytkd.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gt2bxprnfsj.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrtoojjr.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2oxgqhqyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2uzstujfc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhudhjrt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2gueylycj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2amvybtwa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2opsenwbi.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2uwxalbjo.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2mglzizex.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2avhplgnh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gt2rmaqyrag.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gt2xhpzgkdf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udejhnwi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2tfnhslpm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2evqorqak.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2mqwbtscm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpgnqnjn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2zxwalahf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2ercyqclf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2ybohlfag.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2rmtbdoxp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2gikhotpt.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2husksjly.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2fpeiydmw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2nibcskru.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2mnuihnkj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2mtooujmk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2sqvfcrqc.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2ajzyxqml.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gt2vbyoxtlt.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2jjjexsug.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2npmtmyzy.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2adyvgsgq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2gvsdzkhw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2aakjvncl.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2ledwzuhp.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2afewovxj.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2ovghmtnq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2epmzdonl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2eicbnoxo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2cgtkynft.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2kprfxbqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2goqhsosh.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2hjsfanjh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2mhgbnzwk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2aivwykio.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2vwqsdkvh.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2syrlsbah.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gt2dtwoqvzq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gt2hsxrtrtc.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2syzsasfh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fszkqczj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2ynmfnmom.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2tofricgv.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2zthglgfv.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gt2dgdrixun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gt2ayktbwhe.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gt2uznnhfoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2bqscyhsa.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gt2knjbadrd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2cgolkljj.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2svryfjmg.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gt2fbjohbpd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2oxdbfdgu.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2hpcdrhua.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2khbycxfq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2ufifjqze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqovuzz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2komlspha.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2rhfbvdzj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfyumrgd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2kzxinqdg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2lvbcotqd.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mijgooav.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2bnpgpdwm.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjuurdld.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2xhcmwxuk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2axgnddmi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2ghzmlgkt.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gt2htwenawb.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfhtqzfd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gt2ucfaqpki.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2dtptsstx.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gt2hkcweeik.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emsuwxpg.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2lsjhhlrg.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2xyhxkhak.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2cabqemyw.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2czxsvtxt.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2jrjjpawb.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2faexvgmd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gt2rnysyqxh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2kehlmhtt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gt2eqryrefo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2sroiadqc.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2nztqgzoy.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2xhklbnia.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2isbzbbyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gt2lrasoebq.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2vdayjqyn.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2tpffdkxj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gt2dtrjbhvi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2iojhppgd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2aseezqjl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkyklugf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2ggefvddi.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2hcjigpln.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gt2kfryacik.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ulhgyljb.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gt2apnmexzj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gt2oxmkelbz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bukkcrti.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2nfefgfwe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2nruyzhdj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2xfjdseof.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghvfndsm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2aauqclef.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2sfzxttqx.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gt2psbwgjlm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2prxynoow.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2tpqcapma.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hmsytmaj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gt2wbljcvik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2raryonaa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gt2dzgqjpzs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2jrqfzqbf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2vvhhdpdq.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2ucheyiqr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2ntcspykz.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2exsnjnyn.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2bonyomfe.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcczvslu.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzvijadl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2mbgpxrxf.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbitspgo.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2emjbywvw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kmeszdsr.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2kposneje.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ozaxontk.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2lyzkkodx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2chwanszu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2judsxbsu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2ivfgdbln.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2fyrntsze.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2htpyvhar.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gt2fwspuyev.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2gxrkfvhn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2pheeaktd.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2icdyuoiq.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2dzfwttyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbnudego.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2rcxkardg.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2wqoddyan.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2qzdlkbxk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2iumaecwh.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2rxxlyibu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2wcuftyvx.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2bhqgyvkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gt2cikdyrkc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2rxnsoprl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2wfagoddl.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eynjpmcl.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2vwjkudtg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2tfkzugez.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gt2hsjwgjco.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkgltqub.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seatucws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2tyquvlcx.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2vtcitvps.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvmidmgw.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2nhmwiucl.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2csxghlfw.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2lvfrdlsc.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2rwbdfpgb.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzsyrgyo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gt2frlljyhl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2mwygbegk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2abfkkttm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pimbvtlx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.meibo888.top/Article/details/gt2sjibsbtn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2clecnlil.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gt2qwpketuz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2pmsjcidb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewiknqbb.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gt2gvcobvdl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2ndokjuna.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gt2wgjsqlfs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2voevphie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpwzsrzj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2dctelvjr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2tcxlhaia.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2tfkgoqca.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2bneajtxf.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbamsksn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2dixqkuug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2lkxphlsq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wttrhzum.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gt2rdankvrb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2pvhyrdsx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gt2bwygjagk.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwwtbrae.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2yyawrisp.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxkisu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyysjmjf.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kttfqghm.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2jgjkfqfb.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2xzttjmfr.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gt2uizxtykh.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmlhxsfx.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2nssitces.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2ogqfgeta.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gt2cudykzxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2odyzvtvu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2wpkveksy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2uaurlulx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2dgnmuqso.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2eybwpeqc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gt2gwiseedc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2ldtgdusm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2lveifwct.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwxresdo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpdkdhqk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2gydmtqct.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2crbamvmq.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2ajhutbii.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2bgbgluiq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2qbiwrxeg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2cnitzslq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2legukaqv.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gt2odrmkqyo.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2udugqlxi.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2wlxepaks.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2pbqptyvd.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2qzezgdxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2wykpjgoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gt2wukjhgme.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2ghwvemqn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2pmjhecfw.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2gnxbyluh.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2mmhnrqpe.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwrvdbss.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2sexvvcbg.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xbyhlorz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gt2npphmoeq.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2hkhynlof.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdlphrn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2wwaqkrki.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2uyddekyh.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2bduknkkj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvrchfhs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2kyutwlmu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2bdvjklcu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2htruycfn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2ddswfvva.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gt2gfmagscc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzjvqnvb.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gt2nkaieyff.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gt2ygawytpp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2dorvzvnx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gt2mlextxhp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2ohvzrhrb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2rsjqiumy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2jhtnicyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gt2rswqpgbq.html


<!-- 参考信息 -->