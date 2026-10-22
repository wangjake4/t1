代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmpsrju.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izfivkav.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2quxotmhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2llkmqslo.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dextknxt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2syoyatcr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrmspgf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwasbkjv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfxojkb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbfcki.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdliwrac.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpemdemv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwasywai.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fautxtsx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmnvvke.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugtgsuf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbgaszo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjsyvgm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalhonzx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuxajhs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2llnydpqe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pescmtdm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvnojuu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbavtik.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyjijoe.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2knexemts.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iigggcsi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qbszrnmq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxtczbj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2srdapokq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2osioflce.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2spbvpdxe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udhsxvfz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmqdlnf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvtvajn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthtbsaz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpqohxy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkdekai.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrmljiu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvycrsbp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2agoaxubw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2exfnurwt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjvilbd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtmytpy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdnzcon.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uayhnnyz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwlluw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgyffoa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhezmuq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sizkytht.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhhfqmf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoxyrzc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgqsjgh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwegamh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dizbhgeo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcisjkje.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxxrfjy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvptzsl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsifbxs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ointosuz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxdokjf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvcxkrz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kashfeiv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkizety.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxxatsu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoebfcw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eezxmnju.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2twkrjlte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwjfhbf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2inuriczw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgooduuu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kqozjonk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2coalsgnb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2aflpuzbx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehugxaws.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobltnq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lueyfezz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajflnxk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llcmmbkb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxdnkhy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtcgcau.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2icsomapi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvihtuwu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzbtqtt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzljbef.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsongoub.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwogruab.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2plmaiemh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mifuaihy.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrqwdlj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdwqbwl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpfjwfw.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrnahy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwrgbwg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xihxkdao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2awkipsax.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqckjxz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxwhnix.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ojibtapz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfyfzsy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gwouxmtv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mucjzxfo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azdcpskk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzecynmf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhbechc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqdzbue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmmlqdl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwkvnka.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyxjwkv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynblzqip.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stzzadqy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bleuvfph.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbrdrv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egaoalmt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxbcufd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfpzmhc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabcstnj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bueoefzc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rugmyvva.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxnuvop.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryekixyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2prmenevy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mktzunjy.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ispbyrok.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2imnsfpry.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvamnxc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dglbmypi.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaeycad.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2btflsthx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlasgvft.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgmvugf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftextbxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2amatvire.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaovkmhl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iryrybzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hickfhpq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqydrph.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzguyti.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqihtay.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdugzwnf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecseffmf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcvspfn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2klxtpihv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2betxssdr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsjjqbz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzsifwa.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2oyriuolu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmdtep.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2liahaocx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxbtwxb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnukyqer.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsgwksn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhidntd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzzadck.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igeflpka.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcbpuqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvfihws.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2htahgcco.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ympcmtpo.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqtxcgf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpldqbj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdjyac.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuamgspe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgieuec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suqnuauj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrsvhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkgywqs.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wevsfahz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwntuuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeruvyby.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdxgvxr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnazfwc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnxqmyb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyjpebg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlbnmo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdrfyyh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alkxupdz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2aaawzyce.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2okfejvxf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtdedt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhrmyyp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfrzgqm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhskdmb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cewxttka.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxvtnar.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2clhqchci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzfpgsd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpgexca.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzelphg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjbjoxv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexfmqlu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pueiooli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdcuyzb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzmixdj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2uejgcwcu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2abvlcixw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwaookh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwjllkt.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwswxcp.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqootnqu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtoaryb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbubjccu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kihoemtv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmtpqsn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwppkln.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2akvbbnwn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwvpzgf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fttexbua.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfkxjdc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2glyomfhh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwtosbe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkuqok.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbijibas.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npnnozha.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaxtupl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2twjzorfh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yomdjcvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqczyfla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjomamxd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtaoofm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2valmlvoz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2svlkfwdk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rovavvsw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zluzxnaa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgfmanh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyeqqfy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2npznfvib.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfoulgf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnbbdcl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyobbdv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaalgrn.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2khjtmhcu.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2oytrmgkd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlvmdno.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmoaatn.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkajgqzn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpcbhcj.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynmrpc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeleloe.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvlqbdr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfcnsvf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhfcsod.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aijoekvm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqlehac.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2atrawphd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtsfvwc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbojev.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwhrwqb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2cihocfqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqodgru.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2mngleluf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljshjssb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qavzoaan.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdtlfwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xamtwrli.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauycnrg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzohoge.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrllcma.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqdtuhb.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxpkovx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2loufjcpk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmotdbb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eesjvyiw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfzvpkr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcscpe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sknruuxc.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2efrgidsf.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jntthsvb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2tviysisx.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sblkmxhf.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpkkyam.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcofkqo.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlnrjcd.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhocqm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2txodaofv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxryfcn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaxgcbj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cowyirsw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugucgvru.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clixunmb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iktaravm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvlhdus.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tteetdek.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvkvvsn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cilncmhm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtesxqp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxhuvx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxghmfsf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxzntic.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpdvwzn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkshhuct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vehmuzsc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2blnngmnn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrtvuvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkdwjaf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhvxhyf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecewxydo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2makutsol.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2chqtflzj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopldkh.html


<!-- 参考信息 -->