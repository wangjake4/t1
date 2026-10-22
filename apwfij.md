代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsbqgpu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2juqssmuf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmppvza.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtowkdlv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ustexfvq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbkvzqy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygcinvf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzyhdso.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uewxgtkv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmehlzl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojighuhx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2traihput.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcguqivu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cawfhqlt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhglikm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbhreu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwjkwxh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aygwkahb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsdnecg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfwezhf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjtnzpa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuucvplp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2erievgbq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvguyayr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwhksbr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oucowxce.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nprndpty.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2twyjsaof.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctoivbd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjdplad.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kivhvosz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwstguzz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2viunoeft.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2guoifdms.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzkmcoz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rocpmcye.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfabuhxz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sasaohfi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nznyodco.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysniitfz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wisvcrwz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrlwbpt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbukuuw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvnhtlb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnpulsn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwbwiup.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzzzluu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2whpgjepu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmaahp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2urqtwpmm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2djwckjjl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtyovw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxoigoa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjepniq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlcbkqa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2efxhddud.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rggabwob.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkefhho.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyolwdm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2strmcpzy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kemstumj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atvhxejr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2giczfbaf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjitigjg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drdsywcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cugkoryt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2teuxhgca.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cblqgmqe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgfcmkg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptwsxk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzntxvp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwknnad.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufuwxij.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhixwetn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflwrzjf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgiqtiy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dyulkuum.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2glsfipea.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2thrjloqm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbgkbs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspwuiv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoauzst.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpaoahr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqokhph.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzmpyll.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaasapy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abkypihq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtiwzt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aontjpyo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2oavzbxig.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzcpaac.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txqrjlvi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmgofja.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjjxjq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2guokirjb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqwyitb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhgxpny.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaigmeun.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyinddv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqtonwp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyageshl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadejbbb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvywzf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qritdroe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2drpgfzqs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kknresps.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqduulk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfsvtgr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbuqcyp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqndteer.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzvuujt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsnmtry.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjpico.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfslyrbu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elervhxm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qihywgqi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmbxpu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiiodvs.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbmjlpp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmusrnsl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bemisidt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufddkcmf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwkiccs.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2txcvtnyi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ionmyojo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdfwlwo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lolnzbrb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2edyosxjz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfmodmw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2edyfnrty.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbldiias.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfyddrb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2goymmmzc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmkzhvy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kaksacwe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwchjqbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2htskouoz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabxdmvr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkgejxc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2knopyhce.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqowruv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2woanptcc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2locrhwng.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzzadlo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjqlsmr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsigkmep.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwynxnj.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2smvljcrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdpjzap.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpqhpwo.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eadvxlnf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2syuxanoc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvmpcbt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqauvqc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2olpehbju.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2somivirk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2unglfbur.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kaijhydp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2yasohtlq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafehryl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmbneqw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qftsinru.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiplqom.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgqbysv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbtvapd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rrevmkfa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdznfiz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2auorvhlj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ibogoske.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2aulgircd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjmckk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmwrkrk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlddybzc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2umsmuhcp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbdjysk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcrkkpj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsfyfyl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostpbkuh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskslhqm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoohlpz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyipegu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gluvjtyb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qobqrwiu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gikqescq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlxsyel.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrshcitu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2itjbzjsg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjlkgms.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2injyrzfw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2skjloweh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjwccwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhipgjm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iktbxmez.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdozmrx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djxjhktv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrrfndf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdajgyt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvgxler.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpxezbq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2umnkbwje.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjsncsj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdozbylj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpcyshi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsaabyy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzjpdze.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdskcrkt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2tttqxnds.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzchglrq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtfizyf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnmzkcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dusttiam.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlchufv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyqplin.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkncnmum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnfzqxs.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxeiryt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdukaki.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzszmswv.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwttdyg.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpphzaa.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxokienp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2quyjvegl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyzukot.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvqzke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwlbkxy.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxbzxaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqoyyl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rypesfky.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uawwsays.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgyldtz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igqulogs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhwdwpe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsekxyrg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yawsytyo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtbcdtp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcutiej.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lliuevbl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2myzscsni.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqexxlah.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2edfvoqdf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxydnwwf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvrbpms.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyampfvc.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bacbyetl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmvxpia.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dazyimqe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2venaduzb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyczvth.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lssztlpd.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwauiujn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gminjyxg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgahazd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oponlyyt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ticfblak.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqyunga.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpufvpny.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2qolrzfvu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjjhcnj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwcrezy.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvzzjay.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpeachs.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2azujnzhk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2knyacxxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gepkqxwi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2djhlczzc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2xovrhzoq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vigxkcaw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaodolvw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2twqussyt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2txhxahyh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mngcekfk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhngqwg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfiiwjs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjacgwjd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjhscwr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtrzuay.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucimiibw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrlpjgk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfagrss.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ercoaojj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtjgddj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yphrzmpa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2cefsjgbe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjashej.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2goybxdjl.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvntekc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmdoal.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxndurt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2cegonart.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfosjsu.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aahxnbll.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzgeztf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmsxhtp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvitjcmq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kznezzlu.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2klhbuhps.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwvxpzy.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsppewvy.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyiwkjv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkyrehu.html


<!-- 参考信息 -->