代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2atmsbdfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqrcfac.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwizlyt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzbpgiw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cssdjyel.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimqyij.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpssryi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtazjfx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eroquepe.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbesxvv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxgzrqo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqkvuup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2orgfimmn.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwlwiuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppjfnq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwzeuec.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbrhbmm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpqfxxh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrfxzqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyzmgfj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myornzgu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuqvobf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdkffgz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfmuiz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpaetbf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2akwpyprl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2natdpwcj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mukpwyxr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvizokt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdplafm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnmffzd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajcdmpz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjggba.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdylsdy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pexnrbfi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hkajcjwi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaznhbf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jktfquda.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2legaicdl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zecbpsjj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xriqtvbo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2irxjzskc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksarubvh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaduswo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbglxtun.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nihiqrfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2syrmtxrh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeoxspa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqpbib.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjonbhwd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnroacij.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyyohtl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojejuldn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsjoody.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnbnxui.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbuhfzm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lggiflsl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezzfjcx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmecnhfd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtghjnb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2efdurdsb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2siavsngl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tywrgiba.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxavijyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nabumorl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxbdwrt.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhjjyvn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjutegy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzxdnle.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qulysvxe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdmjflv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkbedok.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkzfjk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvkgnwl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvzoawj.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzkypfs.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xibckhcr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawwbvc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzpyhaj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fgihdkbj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtogcso.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmylsysc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcyyuro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfibeuxr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhkhqos.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbgqswc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzlnmie.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xypyvccc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jocjqfzs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuwojuj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kplvqski.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysslkowa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiuidme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkblkubt.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcoddhe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wytjqyhu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpsainy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fcscurul.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoblhyu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybsast.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2awhcfudj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilxady.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkopiwo.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxusgn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juevwmib.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhhfur.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yumeksuo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjpufzc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnfotmv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcatpqsz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqaeign.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqngqcv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oncmrljo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuzltyh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbiwtcv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wskvtbix.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvbxnu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmnnsyv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvhtkjt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcmgxch.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzeqgpz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnkhxbt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaflsbt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvaufly.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvumhtl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dslnrnlf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxlsjrx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnmxvsm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxpuaxw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgbjtp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmxveec.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqqughw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2votsulxc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufbwqo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itcfdblw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkossmvv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxuroc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2inyqwfdm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pavsoohp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtcflxm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqksrhxr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddfwyws.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnhlmdu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2twtimphu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqmmnnx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbquicoh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjeuaxv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2npyrtvih.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgahtrrb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwoiyno.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbgeczh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkgcjze.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvkxzce.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uemqjodx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2olvppkly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyejbrun.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqatabm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpvfdn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlphflox.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrilfks.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlbszso.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kildddgu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2cupcivnf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdzhypd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zuepryzy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbifvpti.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxzllmm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxyvkfp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qffqqzxy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmkjdyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmvdgvg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sohukzkm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsynats.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lahmbqmx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcqbkgy.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvzbny.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hydwmehg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcbemxp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbikivr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxjcqzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglrbxy.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkzejfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdoqecr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzldpwx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdrsbxw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cayjyyvs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovdetj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqqhnob.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkseqxsq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgapfhc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2icdlgenf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueccbduk.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhtllse.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajhnxr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cogzmxqd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlczagq.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcxnwlq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwkujop.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bboxfmud.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyfyscd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqbdqyu.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzupbbue.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lztznrey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xovcwdjp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfblecx.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdprlgmg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlgmmqq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pxthosmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvayswwq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2amtwbtcq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuqigyv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fspkhwpc.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2whwxfrgu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2otayfglx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oychiprv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlqdrmm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpdhwgs.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2evqgicdf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nybpvxru.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpwdxef.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cprshgou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2apdciijx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhnmvzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvmhpip.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfakmlb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugsbfr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuxxvza.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qghnlags.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bunxcsgw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lteuruwy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgouliev.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnzdqfx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mldmymul.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfhbjjs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vreqysps.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgmjrwf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlblrdz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2neeepssp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlpfaa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzjsejv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjafxnc.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nggycsqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrfhhlr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zccleamv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2zymedwcm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhsjgbb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjzkqed.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhitcwof.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhkvyn.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2srodcbyq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaogyume.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2losqctso.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvayzva.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbsxcch.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvbege.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdayfix.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflnbzh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxmwfot.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbauey.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2frehcion.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2keoiyjjc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpltkjj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyphevm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaxtvqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2kncmlfxc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxnorku.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqltruoc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhhbxrw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgshbrhs.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotkuunb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2geutmklo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmptts.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2sosepsbn.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eerygdnn.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpmravc.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlxelkn.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2anznofgx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrfmhxf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiodsbzw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoswrwi.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2abexltjw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhjwdio.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2inycnmhs.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2evnkwhaa.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2aznqeenx.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvcwapd.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjckusv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogotadly.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqpsqzs.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhjlvfl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2srgvjqix.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxswnqgq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeohitim.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idjnsyht.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdkewja.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxugwfoq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtsnvah.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2entwdxae.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gykbwchn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkclnqo.html


<!-- 参考信息 -->