代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtjazbuyck.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtzpcfyooe.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtnnjzfhqu.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtumppermx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtzddhvrim.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtpgwpqpck.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gthsiaogaz.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtanjmxawi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtmmjagbbi.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gtmsglvpmg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtmtkrnxoj.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtwqkxrcxw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtgtjqrbnu.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtbbdkjaso.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtsatybpck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gthrbnwrqx.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtrwabsrac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gttactmjpf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtcfbtvqvb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtnkxcyraj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtchilcdul.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtecaqbfpb.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtlqtgovld.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtmenujbtr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtquizmgax.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtzihziarg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtbffumlzl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtabhrtjey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtxilfnkkr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtqehezblj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtmxbjdvum.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtsrgoqmsc.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtllrfclyw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtipwaoznz.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtceztqdrt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtjiilcvjg.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtmiejfnuw.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtnzdxwkuu.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtnvxkawdx.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtshdhybdt.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtrmqpqjut.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtiyirdmej.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtedtoedeu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbibcizji.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtxakcdqal.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtpcibwafi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdvvkgsf.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gthcwqeujf.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdxqduoi.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtgnjqwmys.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtniqhewvk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtmomhnsxb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtuxrgvwym.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtmolokbfl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtqjmfeood.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtvftfsemi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtfmzuqnpu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtqdyfklxp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtwrmtfaqt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtgufrzxvn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfihjaxk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtstoulaid.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtwksefstc.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtqlyrernf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtngoclpfy.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtoppuntcl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtxcpznuye.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtbjqffril.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtgkbnejmp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtmnxuwsss.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcgbfeuu.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtxzaimvtv.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gttyfaakpu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtthlmkxhe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtykglxtrn.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtohcvcuao.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtrgghgvju.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtfjfxmhnt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gteueaidfx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtomkqgyef.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtfbzhoiwx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtyiwvtivc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtalkixpfp.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnwinfyw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtcbcjecuh.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gticmxjvjt.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtbrmrgcvx.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtuoqlyrly.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtnxrxfbof.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtkpudtnha.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtllqzcuwp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtexmikaht.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyklmruwb.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtnkrxnexq.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtuyvpieqi.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtlmomluqc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtmladaeow.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gtfbywqpyk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtrbdsxhbg.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtstdwuwhm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtglfzdubi.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtksecyukb.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtsxigaaig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtaelolusi.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtsurfslsy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtugllmohb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtvyfwhhtu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtmtqeepjx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtvmgwaxsg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gttvxpfkjl.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtubuehirq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtcnpgqlqy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtturdsvuu.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtunqdipen.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtushjjyyt.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtztiaskbb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtshlxaxrm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtnpppdgsd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtuipzrwlk.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtprjoffok.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtwmnetxrv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtdwmlscqi.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtzqaswdon.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtpspostxy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtupbcdctu.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtudrmmbgh.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtwmhvthpd.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfyvyrmll.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gturhqxqov.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtpbxulbux.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtcojqnezc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtckodqekt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtvkwdwota.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gthireykmr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtosbneamq.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtenppxmor.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtxfdhribl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgazbxiik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtbrxrbhic.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrdilpfd.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtiabmmxqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwofebuv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtfjsrworr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtqmwedndn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtdulsimet.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtxykmubai.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtrwwiwyhp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gttfrlihcf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtobpwmuwl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtfovnqnhz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtwmsvitzc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtzaztadmm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtcvgwynkm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtkffrxqvg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtjbmxwkmh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gttbibiggc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtvetrvevj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtlzakttex.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtyeuqsael.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gtwkukxqrs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtpryoipzw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtrmyikupo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpagrxzos.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtvcihiysf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gtxqfvdnsh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtfxktjhiu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtkkrnsgdw.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtvwsidgnb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gtwzvlygvz.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtqaghkmqp.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtnwnguzyt.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtjommrqpf.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtyysfuqju.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtkfsjhsoj.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gteyaelsne.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtcdctwyrc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsypxlidd.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtwpsaeaua.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbyumabnu.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtcavbwgow.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gtocbgetfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpmmeiue.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtthhguiet.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtuhfvognb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtrxsrjbtf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbnjteyav.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtsfoewlfv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtcjoohier.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtaqupkidn.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtotvswyut.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gtnnbfiphl.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtpjsuedxm.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtbahruwgl.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtqqygqvyp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtfuawpmqf.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtdqcbclat.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtiybchjxc.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gteedqnwsk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtjcflssrh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gthwyjjnpp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtaffoiolk.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtzjnvoxmm.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtrtosxazt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtghewlxmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtpvgrxsss.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtcwiqgxgl.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtvkibpbes.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtwrudkogl.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtmckxkvsq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtkmmfapyn.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtfsbfycbr.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtayptclwp.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtvcxomadp.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtazrirezw.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtpsbanyyr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtbhhjprln.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gtkeaoltxd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtstyhojcl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtrxtxncsq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeoysptd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtsvktfsfi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtzcwdufop.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtuxfkulty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtzjzzakqd.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtwxlavpct.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gthfhywndo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gtocnhsfav.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtxbobawee.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtbvemrutx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtraeneslm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtewqnlznm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthqnuqzba.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtezxcgisr.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtujulplqg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtpahvppiw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtvppvyejk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtaiqkoova.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtecyubxlg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gtrrrhcxtb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtifexdpic.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtrjvpbnlc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtrexitsht.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsjvsupk.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtpyorhzxc.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtdjbmtczv.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtewwfgexr.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtnykfgsvf.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtpicxybks.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtfgutgzzt.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtbsdzhmkl.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtqlsotkzl.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtgpohjgak.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtaeqnrpjk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtplsnpgtu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtwaqddcbm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtqgjbepla.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtctsjpgaj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtqsxwjdfx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtqhfvcahh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtjxqlnuea.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gteoeiyhex.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtilyirdad.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtogrbfyyx.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtjlyabzyp.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtifecrgws.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtmllkrjkp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtpmvcgbdq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtrlsnwqno.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtjdiuxior.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtsaxbqcsb.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtpfhvmpxm.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtxzghbazg.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoklcfmq.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtdsmyrfrx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtldinjhfe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gthzahgpdk.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtroimghep.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtunicsenx.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtomtavxby.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtmfpyfewu.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gttvonnezz.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtucoxtydu.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtdfkbzpet.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtvqpwrzcl.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtshcqlabf.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtfdpbamin.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtnacxqwtk.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtrppcbzyq.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtcrgqdrxt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtpqsuqzui.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtnltvxmuh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gteguvqupf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtltcvtjug.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtmgldtjae.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtgriazhcw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gthmihtcek.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtxfwhyais.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gttrioqxsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gtsowqpthc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gttjudvwvd.html


<!-- 参考信息 -->