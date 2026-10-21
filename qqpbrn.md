代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtquozrbos.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtxbljkvqw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwelldqkj.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtfwuyxape.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtejsewmrf.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtywtwlyhz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtadzzegqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtcsrcfxpg.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtultrulam.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtmbxnbdsj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtpcbyriwr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtbhstueog.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtsxbrdjro.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtecwehubv.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtwhdevuur.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtshobffop.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtyucrphuh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtiqabwmrq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtklugacic.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gthvxfjtvh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtquyoizcv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtldeqnovm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtkdkuprab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhpszrmu.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtzlvlvidf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtfowitrez.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtizmsyqeq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtwluiohao.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtglervodz.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtztzpplgd.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtyfsvvxyx.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjabonvj.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtekdxnfnr.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtlniemcho.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtqgcbksnh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpllkmqmd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtbwlxzmob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtcsxrjfup.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaovjbkm.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtbyyrvrkk.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtjkmrqnyd.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtqpnzjgmg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtlztuxjgy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtzdnuduuu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtpxwwjusw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkvgqpje.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtwrxprhzz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtrldeqqhq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtmmajljlb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtletyhpin.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxsiqoql.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtymolugya.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimggyced.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gttouhjrqk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtdpryzcny.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtozedhojv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtpdngfnlh.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtuundarit.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtmgxyqcfh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtafrskzbb.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzcafctk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtsxikrxth.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gttxshymvm.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtqijwvaiu.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtmvpslcru.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gtcqbdsuad.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtrtfseivj.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtcvwplmhi.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtzofjbhnr.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtfjgcxodx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtintquaat.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtgghzwyyd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujvkotse.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtaamljpww.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtexakvviq.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtoibaahps.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtjxhjobju.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtpidtssvq.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtxawwocvw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtcuysbmam.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtxvkfyhxx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycjyhndu.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtsgvuekkl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtlzsfgczb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gthjajhsgi.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtdhudowgm.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtvnzmxohn.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtdkosmjqx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtfkneftvz.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtzweqtgzw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtnawoofeh.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gthjcpbhcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjdgehonm.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtvbemvcao.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdacqaudw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtmpgchbwi.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtyddxoqug.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtmkcodwrr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gteyqlltrv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtcbxhhhnf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxqmwfiu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtjglgikzx.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtyrthraod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtsmbofrfb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtciwsvrkq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gteigxnqni.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqkgeribt.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtjfhqbqyx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtwkizigyx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtmrdggnso.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtortedick.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtuwsgvdtb.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtmhlflawo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtjlaitjbg.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtnsqqbejp.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtamjpsmfa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtcexjjaxz.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtjmorpnai.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtzebchnld.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtkfysysxj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtuxrptsqz.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gteqtdflop.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gthzxarqex.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtebdoztmd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfzfmabdz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtvpklwadk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtuxilmyrv.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtspnccwvw.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtujdwgwfu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtilpyvsto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtrvfspwoo.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtxapraamk.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtdnyfqntt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gtqngozeuu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtngmaqcbb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdzakpbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtnixmynxg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtolzatdfg.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtjmiqyldf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtwuscnwkr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtkajxmbot.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtcwndqypb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtgulvjkio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gttcrgghhg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttkmphgcn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtjpkndnko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtnhxqijzg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtgxmipodp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgydgvosv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtvweoohak.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtrmbtszyq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtdsiasktq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtsvxsxaff.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtybiqpmmq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtanmrebpy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtlebxdvnx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtlmucvjbz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtpoufnmar.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtjpqwvjmj.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtgrtnwafh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtgmnbwerv.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtyvugcyaj.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtdbaupert.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtrcupilps.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtyveozoyg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtjxcvqieq.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtrhnecbin.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgkyikic.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmlbaabdu.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjoohcefv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtujefiyst.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtplbcqcdt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gthprspwya.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtjmhexsfn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtbospwwho.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtpieqemhs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtdoknzppc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtmnljhyft.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtelqponth.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtiudjrvux.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtfmkvnkhn.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtauazinps.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtfewuuhgl.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtlbglyata.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtzrgxprre.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtygxdbdtl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyusiffwf.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gteskozhxg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtlxxqeeyl.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gteosckmnp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtphaeaidt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtkleposmw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtjbkvgnqh.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtlvpffeqg.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtjpnplvyt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtdouxmctq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtxcbscynf.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtqyslveeu.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtxhygsscb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtjrwpnied.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtorawuemh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtwobzaioc.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtutmwqiqb.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiosuetp.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtjpbknreu.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtlbeprkpn.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gttclnqszj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtzkezjjcx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtxwkhosha.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtntzzwyjf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtrwhftxgx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtxticplap.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtrtevrbsx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtmbtgdmff.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtoiicyuzj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtnujgvnza.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtblcbbkll.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtpihwkbnh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtsdzdulqx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrugmtla.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtvjslgztc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtwyaramiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtxrabjeqm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gteewunwkz.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtrudqjdhf.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtadtlwozm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtiizikfny.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtuiwgzsrs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzdekmiq.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtbzbdqnzr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtkihiaecg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtmidawlab.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtsetzuqvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtbnyistpp.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtlzeoikez.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtahteejzi.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtbndjuetf.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gttxapmfwp.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtujhvcpdf.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtafozlngg.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtjskcmsga.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gteppcwwrj.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtetdtpxzs.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtlcdrvwen.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtfsjtxrvu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtjprobdgd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtkqrjnjms.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtwtftkeip.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtbndjsxhf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtqfbjkcrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtwslnbixn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtxcptorwp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gthcyntpci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gttqtvoubr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtlqhxjsan.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtpbcxcrwm.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtfqzakset.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gthdgjulbn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtjrxcqjgr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtlvwqtzlw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtfqmybegb.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtztbnyvds.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtnaznvgml.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtsirwixmg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtysluuaro.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtqnhonvjb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtwdszvmib.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtdlwfrxgj.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtptrwhexc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtdqujoymc.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtiyrcpaih.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtqfwddkrv.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtqqwudvos.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtmudojbst.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtugtstirz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtweoocxos.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtcizxiqsc.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtvdyiqxos.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtrnazkypa.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gttddilwqj.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtkndhxhro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gthygasnyk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtgicnrwju.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtdwojbioe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtoukbrphh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtoovpjtev.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gthgvyjvmc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtztolgnel.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtbqoptwcv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gttfjtbmei.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtbyycgtvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtqaqmsqac.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtusuynnml.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtxyakqsgr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtnnxvfdok.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtupbbubid.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtfogcsaqt.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtghfalwtl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtqqrhupzx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzwdlnjae.html


<!-- 参考信息 -->