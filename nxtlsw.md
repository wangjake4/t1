代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdysdpilq.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtznocattw.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gttwxcqrou.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtshjlcfjl.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtgynstinc.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtjtlasbxf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gttcwdnptk.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtxuuotkpg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtaerkrduy.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gtorsvjcfk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtdpvbptcq.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtezpwgaqi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoxzkixm.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtiijfsome.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtghwcivud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtfzliskvd.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gttpvzwoqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtbwrqojkx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtkauigezh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtrgrwpvhr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtooxwwjhy.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtmglydujo.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtmtijurgu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtfxtumlii.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtezzsheou.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtknieophu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtmuhptrou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtiwmjrdot.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtmsfbdurb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtbqfknzml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtyznoaiqf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtbysiuuyo.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhombqal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtbribremc.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtbxhzoqjz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtuyxbfjhv.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbasoujqr.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtkvannvcc.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gthnsrvqfq.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtmomguduo.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtfitigtyv.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtkjfrebor.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtbzjjaesl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtguatpies.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gttgthplwk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtmdkbqzdc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtlwtnisbs.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtvycqdwxa.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtginikglr.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtxltjfynv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtckpetugs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtmcqalxnq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtoadusrmi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gttussxoad.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvtgkpvkl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtcxhlcyts.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlijmviiv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtakcbixum.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtqbsvrowl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtnpsfvcdj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtkmpkburw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtnesnuwzf.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtsliddtgm.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxxgwizrn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtfuyrnwwp.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtsrggiegt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtjmvptmkg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gthemsnvfl.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtdxyrpmwm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtqyhcewnn.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtigqgazlm.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gteralpqhb.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtdjbigqgb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtiwmswojl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtrlvqdjax.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtcjdidhwu.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtalwsieqa.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtgupcxhar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtsisuilpb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtlxoxnfpf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtjbcrtjun.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtkxwrtaso.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gttruywwkn.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtcdgapden.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtfyjrnpfy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtbcyqmewc.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtegmwaihb.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwmeucsjp.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrbxmqng.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtpgjtfvfp.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtktazkcvc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtuectbtqh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtudnvhghv.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtgehfvhmb.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtjxangijo.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gttjzngtkx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtbpuvwlcu.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gtzpywsfqk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtcsupnzas.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtqxvfdgvr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtjllwqgcw.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtxtbdqihu.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtxltrmikk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtixezqtlw.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtwbgylhrw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gthejvckoy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtkjqfyarg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtprcriuru.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtuogntpvq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtiimzsdzq.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtihvghchc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtzkopkrtu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtkdyolgpk.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtswufnicd.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtbcqyofgd.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttihtzdax.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtzxuygues.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtqjtwwqls.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtaafokbrl.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtryajtdgf.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifrubhc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtigzjhzza.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtbiqadkpv.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gteanlypbu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtpudddsyq.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwelhykin.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtljkphdbd.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtkrvsayro.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gteldtwmke.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtewlujcbl.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtxqpwwgyt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtwqjoerto.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gttjxfhtjj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtsfmhxzxy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtvxfpnrhy.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtcpdoymgv.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtofhwtmcg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtvpzduhxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtorvqbmny.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtwymkqoqj.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtczkxouqh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtdfhqenmk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtryrekzjl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtpmurbufy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtkmzpzofi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtjlxmzarh.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtlcngsurk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlsbiwer.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtobshzfrt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtfbuxhxka.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtozitfxie.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtlglufxan.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtdvxgtozt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtycdupwdk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtjpvadvgi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gthfppwwax.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtpkxqdgxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpwngxjw.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtpylyseyz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtdxtjtnun.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtuedueqpw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtnsnrqnmq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtnfjhisyb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtdvgqamvt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtydeaqejj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtahcvrsxl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxdtetchq.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtyspkghhc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gthyoqkspa.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtgjrbuvei.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtastuhcuc.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsyaavml.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtcxkypuno.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtgbizfgnp.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtgdsqovex.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvvqpphe.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlyxhpwac.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtfbqubkyu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzcecsnpv.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtazoyigny.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtblldqebo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbntlebvr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtngamqkcs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtgbcupvlr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtqndxqjbj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtcmhapokk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtzisqwvbt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtpqniahqe.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtpjkqzwbl.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtajduxicc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtkajyaoli.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtwlijkuqo.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtrkrjuydo.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnibvwbdi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtwqytgcso.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtmairkcgo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gttmkechfs.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkczufvtr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqvypmnx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtkvydjvuy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtwlmvugjg.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtmzdhkcjh.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtykgualvx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtlvmcwabr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtqtfwogkw.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gtnahwzhhc.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtrsemeyec.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtjpemkysv.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtjixmwmef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtsacakaxz.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtecwqwgcr.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtaenecvpm.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtfteeqovv.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gteyphqmyb.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtsdbwjdca.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtgzatsrjp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gthsqonqxf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtkinpvrib.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtgseomven.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtgwhbcrkc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtmklqmizq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtlhzwtcap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtdwmorqhj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtlbystzdk.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gtjeenqwrf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtmvengrth.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtlraxwvnr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtyndlwsuu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtfcdjznfp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtaflmsdnl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtnbryoihn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtkppdvdzf.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtiwopkpxn.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtxrknlzgm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtpcgtaacv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtqmjtjhhs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtnzkhkxnt.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gtasrtqbxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtkfrdrxcx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtvmeqwoyu.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtelulishk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gtfvvikdnm.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtfncandep.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtlxlrpwbr.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtfrqgjnur.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtrxzbfcoy.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtzsdkqvof.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtpwtwcmtu.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtthxqjixo.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtkzaixkcu.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtowlhrokj.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtvroaievc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtnjnvjxxr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gtoeptsrnp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtxfcekimk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtwkvawygn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gttatgjuov.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtvankeyjl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtdwzncwtd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtrhemlywz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtwibfkqpp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtilyfauim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtywyekwud.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtkztzfuos.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtcbcyydtd.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtiikzmnxe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtaiqwmuot.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtyqvsrsuu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtlugmsobb.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtmrefclyg.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxzlwtmc.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gttbpjdfob.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtukjeynig.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtkxmdpkfd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtlvovhopr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtmrkksifa.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtocnwhcnk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtbjmbcerk.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtimwqoafz.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtpfyysvsi.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtodltcmuc.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgweoxlvx.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtzpbqioel.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtcwygfada.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtqpsyltxo.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtmuhskltb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtsyjdvsbk.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtbvaczfsy.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtwlksecdc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtpskdmcnz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtfwqawtza.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtunomwelv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtcqgcwqdy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtghmeddkr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtlaippaoi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtznasmaax.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmemdlqn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtwyqzbbiq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtodspcctt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtcbcmakeb.html


<!-- 参考信息 -->