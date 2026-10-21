代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgruicie.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtqvctlzns.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtkauvvtor.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtfgodsrvm.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtolwvqzlr.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtxokhbmru.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtajaycnrv.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtebbjypwx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtyoevqbiy.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtnxgsddou.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtklcclqdo.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtcyhewtkj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtptkqxssj.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gttnugzevk.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtyldmrszt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtboboqcov.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtiyxgmnyv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtxgakhvsq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtbqlfaudr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtfibcfmmr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtyjfxjnxv.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtdleighxg.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtehviyvks.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtheekvvcw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtpcolnjqr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtgsjlravh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtmltqhoyo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtshszdurn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtknfutaff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtczmwiksk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtenabxwci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtwwokiiua.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtdedkslrp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtjlwbbfxa.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtyuwwsuli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtwhsgljxf.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtuugqupnk.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtmxbvxdnw.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmgmrqan.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtzcqmgcnv.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gthffonlgy.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gtbjwyikny.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtxcillilq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtvsrzdomc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtxmfhlrev.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtnvrjngkh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtufgdnkmf.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklklulpf.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtabzpidnq.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtyygowfil.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtjmxcysxf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gthezatglw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtfdrnhgzr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtezbzwhjp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtmxopctyb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtgqubktks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtlhftcggd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtbhxuvflh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtaftmkdmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtapujvhoo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtyxzgpgkw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gthlxcpktc.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqapxlal.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtfmzbtznr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtmnclgods.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtyihehlxm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtgsemkuxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtaiymtvqx.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtewitwksg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtfcsjsgcj.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtfzcdxphx.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtsbknduek.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtpznngewf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtpsfvezdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtoftkspsp.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtrtrecifs.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtktpwhaqi.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtdkpekhlb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtngykfdhx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqbjpjlrz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttloynosa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgaiuemye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtqeoqylwv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtntubjxkl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtomnljyqi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtxajqgaps.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtpapnlidx.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtqegvfqov.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtfqkjshqc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuexpvdrm.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gttqbpojpw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtidrfiirs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtsqxlnidn.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtgvrhareo.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtuyrknypf.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtuzmxgchz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtwsqkdquj.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtiweyrxks.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtloqamzuz.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtyaelehxg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gttjlvniao.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtcoektgot.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtwkgkqxru.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtradhqsfr.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtpjvuwvod.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtlvfhyecu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtfnzdczpm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtwypkhato.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gttvbzscdx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrvojpcl.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gthcfvkdlj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtapoghlha.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtgyxyrbnr.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtdqfqipwq.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gtwxeubwlg.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtzxdjxevk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtcqpofzls.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtqstgfqal.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtyzhkdsnj.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtyzenajlx.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtvrcyiekb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtpqfaielz.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtdbzsgbyk.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtkyxqdkhd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtfphuknyj.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtaovjeqfu.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtolmzcpln.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtfzribtkz.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtehtlxhtp.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gthjipakmp.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtkvpyswbe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtemeeakyz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtwlkuitqj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtpeyzgrvz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtgpmqoosq.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gttqrhxhrp.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtugdtwqeb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtmhphwinj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtnnxrnqnw.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtcmhmlpxv.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtljvibelh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtzemifmdn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtuhkvarjo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqexfqwhr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtntyiphao.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtikilaxpr.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtergbknkb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtsgzpmkvv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtukpxpegi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvprxyvb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtwljiykji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrscidzts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtkmvkykjv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtxogkostv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuymbunn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtvdguvtse.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtkfmkhskb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gteyqoceit.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtkvcxximh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtjjvofxlt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtbmhwhydn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzobzrwx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtnpbkcdyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtbaxvadjq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtvnhysuug.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtoheudsnd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtyvlzkabm.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgmsjdlm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtzwlnuayo.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtslyivsde.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtxsnhkcjy.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtkbydwhai.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtlekywmdl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtbndgfarc.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtixslghda.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtcvmjmyir.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbsrrapzu.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gttaqgkegh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwirrnpna.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzxjifbnj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gttpmjxsdb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtigtkszqj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtrpmghghu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtrcygirko.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtlkrnznuh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtlkvsaxmv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtykgrdasv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtwufupcna.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gteewcomyt.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtibkgzchx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtwpbjgggr.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtihpsvfdm.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtroppdkjt.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtdhsnolyj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtiuqavspq.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtrxdhqlwi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtalkueynh.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtlmhcrocy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtzrmqzivn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtdmyciach.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtncefrmab.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtwuxruajb.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtvnylflmq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtceyaouns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtzbqdvwuz.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtpyoatxuu.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtatjtrvpp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtzqecxvdr.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtculimall.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtbrujsztc.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gthrpezxux.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtnwhzhyfr.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtoprpchxb.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtwxlvdxqp.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gttbrhrido.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtqiaushsb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtvnfzspwa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtipdcxnxi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtikqlfqzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtvcswghve.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtlxaxyyrx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtyhwhdddd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtiyzdmhej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtcarkbyvh.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtcwnmzixw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtszyljysq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtnreaoinl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtfxohispl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtmtgvmdrp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtizppnniy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizcxcgue.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtuxopjqtn.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtxzdpdyyg.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtdqzxjygs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtckeotuhc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtkrzhatwu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtvugcvfmc.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtxudeymmk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtjprvbvwt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtkqlvbmyy.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtruozjqsd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthomaijvm.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtvwwiqzxv.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gttizthgnv.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtqzywjncs.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtgdgkqyyi.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtjdizueat.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtgnqqfvez.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtaugvesho.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtzjaohewt.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtoeaopkqv.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkhbcalx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkcatbvfi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtnpvgsgke.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtadgyenur.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtwpibczkw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtmnkjxdah.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtkrbvlypw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtdwbxboxj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtptieaign.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtgpfepqqi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtjyqgepky.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtaxhfeedh.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtpizazttg.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlatfglxo.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtfmscperk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtrviornfb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gthfwidjcf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gtgnazhtjg.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmszomvht.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtxoahhbad.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtxioumplm.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtnkhpnywd.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtgwsdztdz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtjlrujlpm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtdiungsrk.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtbgotiekz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtemflhqcg.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltmjcuni.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtnkpduglw.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtfmwvtpie.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtzslxpxge.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtxstkrhxz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gttywpbxhx.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfmanaph.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gteulatyag.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gthmevlzmm.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtwoxccozb.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkjtudal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtboayyonu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkxgqmusy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtsnzkolss.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtkiyxjkpa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtllexqckd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtgqitxryj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtgtspmvqc.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtzykbfvvn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtfzjwpatx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtbhwvznkn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtxakcxwqc.html


<!-- 参考信息 -->