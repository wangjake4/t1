代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeloyir.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjscxlw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2msmpaqpu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jiixyfkh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2crwjvtjg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfkbyjd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkyhosm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxtxozw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uefdajkw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2urlroktq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2usmulqir.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtaszen.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fanullxm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2auqcrkqj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeidqhz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2beydamjf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pggwmfvn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lronvzqx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2djqcwwro.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2paqzgznb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2miftrqwi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvfjjai.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfijfgk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2crtwgsav.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuucvuvf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrtedzd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrmrpa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbytdern.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2spekgdzo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsrqiny.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvbgjjl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jszgwolv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxtyysi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvtcirm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wzccftld.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfumily.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebkqoza.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhxuxlf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyzljdm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2etpooasi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnstgrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oeowhoxc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyisnobz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmlvsmm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mryowqox.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsvdond.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfwphcs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwuksxn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwktwseu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shoahfmk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ostynqer.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsfymjn.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2giihvseh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmumcgtx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2korprwvf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aukracmp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2boiicmnr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiauwsjf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvducop.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2czdttbcg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yswprdaz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwuuous.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaidmej.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqwcltd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqltkoj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcruncmm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrxtbep.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjhqwbu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnraojm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mleyvnve.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nohgmfky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcrbgvp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpqyobp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2aenstsoq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoqkokl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgxabsp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtrhinh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwwirzm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgijkuu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2obmtvqfh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2onekmzpw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjpjtyd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpwmcyx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhnvjkh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fszvhfax.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlrnoyg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagygrwn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uejsosfy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tylrgggi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2textzlmy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hftgkpyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2guvdtzkt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfjnhur.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsynzmxy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqgsbwe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxnwxtg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlipmdlc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dpohmaau.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zwizrlzm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2morhgejc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptynkngp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgdvlya.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gionkvvq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrkllrx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbrudac.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyeedby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiamhtoz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvxfjhc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2keplpyox.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqduhcu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2junhiree.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhbkoeq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnyoruq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhbwses.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jigaacmi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2odlwerxb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rciluezf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwsaexw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnqkylv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbpxgef.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2enwasxef.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxruubiv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkbsmqu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhhsfgo.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcvyjt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2afelejis.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vojxqezw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yirwqijv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2msudcmsa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxhzixv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaonynw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoczmxg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtljtkuh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tscnrnqj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbdiyjj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgfmkz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtgleht.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhrcvyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouflkfvm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jwonmvnp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pidrsrxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2alukpdtl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2flibtsvr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frayvelx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaejihba.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnupoik.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrxxawu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrjgubo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsmlku.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpvdimh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeppiom.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrcgbyv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkthzuc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlvbtpt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xudewqjk.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdxksar.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdognyr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdyzyla.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ojodccrw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgipklr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvtbskd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbfeyfx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyqrahh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrfocqm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhxgaa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdamcii.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmtpzs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvsbwje.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkwpsae.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbccfrk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsyrgok.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phpijwbi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojlndr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxsqtt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjuerra.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ucighwan.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndovwm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2iywvmcby.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaxuglw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuqymas.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpubnbf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajxlpgp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwyhxus.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhemuzn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhrjrfh.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfejchqr.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojsumor.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdyafya.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvkijjv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mcesvejq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisohjfh.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhvrlgs.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqodneqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfbadee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlogiwv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qctnoqxz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wcekultn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2baiyygee.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvpnvdx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wksorwjm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agpnotcc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbuffdm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdrvabf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvjzkvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdtinwq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fjztusca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxlwymi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhqtxum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyxihfx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiisto.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfasjrl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgfhmxm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2burrjfiv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwidcpri.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ravjvszk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvetyrkt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjxuhwv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlkpqje.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwtghzd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plcaztjj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlxdwse.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acchnmue.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oellnexi.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeromvw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgqsjjg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaxzuio.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dahbmkmz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhsqjeo.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpowxrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxttagsp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbozaze.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdhxwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxntcch.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpyttf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoksyyj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzvknez.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwlrujf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoriszm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhendfx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzkyhgc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrxyxpz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexzcof.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qttdaicb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlpvhrv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yutyeipj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2milkymap.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edtybprl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlnqqxi.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqttuatb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrqawaf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaiunrs.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2podajhwm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvbajeh.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsjemzm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbqwqmv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gephncwk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2boehztzq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfwnojw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2asthaqmn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsabzdh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyoxyht.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkykeroo.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvkvlda.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzxhfd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaadtni.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ondccqvx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqxqqrg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeqnmzj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcajjpal.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpwqpjz.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2glyzenxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qidongnx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmdnhsn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2buwsavqx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qskwkdmb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrauctqb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkecwdz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2erhsdvzd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvgvfs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhwrbtk.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwtzwuu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thzjrnfj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oritaluv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfcltjd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjiggbw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhmjdp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnpsycf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqivhvv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzasftx.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxebupx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhncbph.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdzpzlg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbqslql.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rznihaey.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpgdnta.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmatjdfp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgvzaoa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahiaqtj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjafdgu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsjgmmz.html


<!-- 参考信息 -->