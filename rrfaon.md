代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvzepku.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwohzhav.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuupyrl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnzhluf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omzfuppp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpwiys.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndusdn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnzrgry.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqgfuun.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpbgmno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyhdpsa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fbigcefx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2byybukhr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufwfhsx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxdtewg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvpvjna.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdspckmn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpgpeor.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpixnnps.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyectra.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeecsku.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdsjxbo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2piitomjz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuxqfqo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvtohm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsmjosv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwzctdr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxhsfl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2garvtqkx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuouiayd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntheglqh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2solxmwyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fugmdjyo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pndtwjwm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxfivsg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cogetcyd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfiwmfq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvttjmy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2etxoemxk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhhbfcr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvcsqat.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrfuvip.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmbbfpu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwxvxk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2farhqkwt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2npevnvvv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcivhpq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsqdecq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiljpojk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxagcsoz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtypops.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2adcxjpye.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbdwaqz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2muvgqpdn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2etxbpnev.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsszomut.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewtbwar.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rppdadgc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2blfslxir.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kouumhxi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtnwxtt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sssewwme.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hamihzlj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqmziv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugytjayr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyxpmuo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgljupba.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoajejn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtaryzv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjfxqlp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqqhbyn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkknrft.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dghqvnbv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyldzbjx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabkatwu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhtwxyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2efyffdbr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrgdfqc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rieqqhot.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2alxzodam.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkurbokl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnjllee.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwtuubx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkfnfzh.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtlmupz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgxzjvt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfksjb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xziudtlh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlznznsq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fkasppfe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxucxih.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrslfzf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfbjhnk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2baavxycn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqftcgl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcoxpwk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgswqdd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kybtjazv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2refcexis.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhkdkir.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngunkjjd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tknucsjh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2szielmap.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tljpnivw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwdtjab.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvymztyq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnyiyqm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rizmlicm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlprumb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeruxdx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcgfyq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwktng.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evufemhu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kddriwfx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxalrqsk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygesfdar.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhyxlpe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eubifovr.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2alysgynf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmajgbw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyltnyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoyursi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2itjqnwtn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2acxiiitz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gntobdzh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgnbjnr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoprbbw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkngxza.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vieqemqd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zasnsfmi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvzghew.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgvljdy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvlrjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgsogjd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjhvfqi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcddpopl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmbumgy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptknjpcm.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbxwnx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjhxtme.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhblqbjb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmdeffv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ousxqhir.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkwrwrv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvclslm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdjufii.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbgzlya.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyksfmld.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhomkrj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkjqix.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkwaitd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnljxfk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2olkvxmcl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cytuwznd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2iujsgdui.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfdcyvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzkzdvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ioknfhnf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyizkzb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzdytks.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvchtuo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeeidrz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrrsyjo.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlxgjng.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnihxvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdxvkyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zprcwaks.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwnrgvs.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnqqvqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qcroibvp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2trzuawcz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrrhqdy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxogkmqu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mblipwfv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhewzhoh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srrwpvsk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhvygns.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskkkjso.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqzyeay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpknnkx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpuftfo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2npvadogc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkyehnq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaxtaqr.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynysbbxm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfcvcek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyunnjl.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvvgodk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtrohib.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaouhzz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecghchhb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhbpybx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopkoen.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jycqhymr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlztqme.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxyldaw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyztwzg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbexcuda.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwxxfwb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pplketod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiugptbp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaayxqht.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaxmuym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvvysrm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2agssjcrx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxopkwfb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgvvojv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wffdjsjh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bvktnovn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjlxwdw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyldsamt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbikifxc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyththx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2delljzkq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpxlcmz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2foozhxpt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbcdvql.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2taivexkb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmijrvg.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnovxgz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjnzotc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2upxkkedi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpawuasi.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oicfjevk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bipmuach.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qryzzdea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcsyolj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adxkrhly.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2msoypxrx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlbnhiq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbgysms.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2khicgluj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2buhbotxk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqofdixl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2yljaqier.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrppqhdm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjlmpdw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rsemwhls.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrksbvcr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgrfmij.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodhnxfl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwodxnpz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2faludszt.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jklcetum.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2srwzazre.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpvithr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdfciak.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyblejiz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiyjnxp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oedclcal.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2svukbkjg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxhpotm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmozuwnk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2srbtzugq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dfepejvu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpozniaw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pukhrmnl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwgontz.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cupjahzq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaitzfwn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfjtjsk.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrsbdqu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtuxckv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zlctisuq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwybldj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgmedfx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqecmcu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnpabqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yodiglnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyauykix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqqrqki.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsksgowf.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnqong.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmqllzm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtafbbi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmfmxlq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuatfbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuadfqy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnftzhcv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhfdowt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2driccbkz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gprwzyiw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2brskxech.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2toradhzz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrcercw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxfqunk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2myaqdfps.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuzwadt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoqysmu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqixvbd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfhgwab.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsncuzc.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbjmezk.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwcnxro.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlifndie.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrvtsva.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmpolit.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrvskqz.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrploift.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfvlkbx.html


<!-- 参考信息 -->