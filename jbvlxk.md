代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vloqipsd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cazfnwrj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oocnuvth.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlpohlp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnhxcyr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuijcgn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbepvah.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyautokm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thfylors.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2akczmztz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzybgqob.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyzzsxg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktonrems.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfahfdq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcogeeo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmokcrxf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaajvey.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aggayzmw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2isftwvyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yslqwqln.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iorxnbci.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2imwkzekt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2onitborh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rggmihtm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxznhnd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfolsefz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2quxyfpua.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoeingu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2crwgqfrw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvffdqg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kunjtbox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcadqwo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qayriqnr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyyexag.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iceglaoz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jocuzmzc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubttkrtp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2embnvnrp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eedmxubp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2trqqhceb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrzvsyu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjduvrsg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dylvydwy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwobsnrs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkptiqcp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2feyexibu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egmazezn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qubdvagk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srorwvkp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gknkjhxc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuzormy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xihzqxxu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzpspus.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsyphfw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxeofbf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivkvfve.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edkyagvy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ostbenmw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgloxkjy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2omeqsauq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdzzbyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjiqxf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrtekco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxgrblz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oznqsxkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyyanov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2usesnuth.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdoxowk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwwcywo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqknyme.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrapwzqh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmifurqz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsotgum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefxkic.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwkszqp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uziyuzlp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjqoywq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fitvmzmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2incabwaf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqrzamt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mulrwicl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2szolnctf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kebzhkjd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2axjmqqma.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwtqqpb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzbsiyf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczvrghe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2thlsjbpo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sprjumjv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgypxaq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aoscpxlz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeoccca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjkczyl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodapzpw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tazthopu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2josrwjya.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkslhhmk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbopppo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlektgh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2icgdliva.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcczjhi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rburqhdt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nseqyzwu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njkdkhme.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2clanvoiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvngkkco.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwgjao.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vewcsqyg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcesovvv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vscrsrlv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ietpkeid.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjbdqhl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xttgtwnp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpjigcd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinqrtxe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlbsdkq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wmryagfk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqldcxw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lufxdguy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjevgnq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqmjorq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kashtqis.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eimugjom.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvghnkx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fadqtfaa.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtjqahn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqjtja.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiljjwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzovhhm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgewipf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2epmgnkwl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vwltqkda.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tefmhxar.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtokrmix.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2thwvhzpj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2texatssc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shsmveey.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdbgxrg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqprkoec.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdullzo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwcnwbx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wzldsqxh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpswhssz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbytxoi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgifpff.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhpidfr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadunqia.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduxhiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tanzxlcn.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrprbtvf.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rowntftu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmlbyar.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wdienojj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqugzrpi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgvwkwz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvarafk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkvtocw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qislrbpj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjzrand.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxbihmo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2waappoty.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgdbern.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2finywshd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2exkfhtqd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iyowjjnn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzkqbtw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtghsqy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfwmhro.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqegzas.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwthuba.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2arsfzcgg.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjakzvi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqsshov.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jspzxdif.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrztwnd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdiayew.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snriodlz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uducouwq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqohfas.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhthvxls.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfncie.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pbekjnxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbclcdsk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpwabgp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrzvzoq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tskcwdge.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2moaizmjo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvosqzo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmxwsfs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjjmgvi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhdkymv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhyrtyo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2salgtllg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxerxfhs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvawhe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzvojuh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwciepfz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2drjlegau.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2arebpttx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xydittjf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slaktlxa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrycvzf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcjbibb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyptirip.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2blspabqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqftrzw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnprzuy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nshfvhtv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2etlmedws.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgqwnem.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeufjpb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpwvsmj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ithzkeeq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkluwwr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphfndjy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eatgpvep.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrjudb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yitjonhn.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2neudusmw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdjvpoc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxtntrd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfriivwi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevmkvea.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbzwhlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlklgj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmhqdzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcmefkv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kygxxacy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbxkpvb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaftpah.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sokhlnoz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcoygpu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxdzqcy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtsuait.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qujmpsvx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqlukrw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxflzqb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrjiwyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfhvanw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kudrykqf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoqfmvk.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfissgf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqplxtr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjdyoqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdckuhqo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyktipe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcescoxh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tblurbrq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuoalez.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjjzvp.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cposijil.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lleldyda.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uklrovhl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjyzlmn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ohygnuad.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaybndx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaoobor.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqaxwuo.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkkrqif.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvumkiq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqjdrfr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdadforf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2estfztik.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fezvxvap.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxkftjz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2uznfsjnu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiplnfg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2manbowyz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlzbeqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2siqprkjb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2anstrmab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iagllrbj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rioakpoc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umfqmvoc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2komjjjvz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzvavhm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmzvugo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbmybxe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaaguuz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgajqkif.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztftdscg.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpzgwka.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbsytdh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2adnhjtps.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkccuvjy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvmgtuy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsjbsbw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppokxbca.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2eamnrftr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeejfjxv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpfougb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygufgkwx.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2khtevzae.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxddkrpi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfhlsom.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupgarxq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuevmvl.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcroepx.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbnqqcg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2townatkk.html


<!-- 参考信息 -->