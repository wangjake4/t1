代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2axmgrdoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nowufteu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujezthom.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksubhlux.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjzbspx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhpkxqj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nacntiuv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lycsrfyl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phvzupvn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebvtyom.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcabpwr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lredtrym.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2urqkgkvc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2avkhrpff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eausmklu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2spwprvls.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2evqbgafv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkwqvwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iigrlwdx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghijbrxv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwppppgf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfundnly.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rupjmnxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifeufqd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iusmvemg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnkjtcd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwokxbub.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2trnxszgp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgciklz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdgwhfd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nojblgup.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nheoambq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eudoyycg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nizilbxr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2spsktdcz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wmehjfxt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdlsvro.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzpygtz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgocfg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbvjntf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjedral.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthiyjxu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2epgnawyy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvvfmda.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwsgacj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2twlaejwz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gawcstem.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqqxrzf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrupsnba.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqpdxvd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uygchetk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2anflsmlh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dimmokxu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nknuvuqw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhkpyxz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2audlvsku.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgardvk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jacyurep.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kahxjytv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxyqevs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaoctcc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2leowdgoj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2apoilbxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjanmbi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsqbnoe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqmfro.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqpqiqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2asioupha.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgcefbe.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbzvhhw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjfzqkm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rolqqkul.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnydkde.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlnyiez.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2parahrpv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgelhnw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2icbqsjfv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmbqjez.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxmtlbu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpjqytj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvmtjol.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bboceene.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjfewmu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyizufgq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzlccrn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2devvordx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxllazeg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hqltxfsq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfncqphi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpaitfn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkfxmty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsthiwa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkzjhak.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgmqkzc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvhcnxr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjariynk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftgrtfs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxkqkud.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbhfehq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjimcsd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2koqcdyws.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkqlfcq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkkotue.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lniykger.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pfswakil.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwcpptq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kattokdd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2unbleael.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtiynbe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgczznu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeesqsz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biggxcmu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vplbdubn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oydmofos.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjijjkt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2unzhhuly.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yjusddgy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbquurrx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzovfpy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnclriy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fonjdlmp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2exvgxfwr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2srspiqsj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2inhgjbav.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcfwfyo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdwseqb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asnuxigh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idzddbds.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsqoein.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2durqzzbh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjflrpaj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeaihpi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uffzrart.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrzbpqw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgncrtb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txuwywjh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvtgctg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdlkmjk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2arbdbiyn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kigxymrt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoklqynx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2khcsqfen.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxcmgeo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rucqxbls.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2outzoddu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcdmssg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2feyybrsf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2noqnxsbl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvyhdtl.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidtmjw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqybpdy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2urblqvot.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkhkfyf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjhaars.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbcuqde.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnigvq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibytwugm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2avahmvaz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2asmhjljh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eojpijew.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnbkyrv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyrjjao.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaodnvs.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhllruq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fybnvhbq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yipwlauz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2atfmwjyw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yuapvwjf.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzgpsjo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2uufvpcfu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkinhmp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vltxtkoe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhizzsc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwefrwhg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfzspox.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbqupoo.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfilmbfe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxtlalh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjqbcgc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsioykih.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjocqry.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeadwuu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhqjyqz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxttlobe.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvayqow.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvavdds.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2adyhjsbg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjeqccz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lhprvqgr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcvaaaw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdsfhus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flatpvbw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmmtrcr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcleatof.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jgswpecq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2opeaznyx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jghotomj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lufupxod.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfaaxhp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpqhdei.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpxtlfk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfwubsz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdipsva.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2otkucouf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaisfpbm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2apijrhea.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2splancov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnctjkzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwlctsm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvujgzs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nweiztds.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxktchgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgzyvwi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfshll.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlyoexf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chtzmhpt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfghlfs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orwqpwwi.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfkpgju.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yccduafw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwmweqn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgprihk.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfmjdyv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkxrmtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umgryiju.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnwahgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbacsllv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qihjzyia.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhilkcc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qykbndwp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2coyucimn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyazyjq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bejedpkt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2piapboiy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrsakmw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuswgjts.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaxprpy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qwezrlsg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhjnffi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klhzxxkb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyquoax.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvlnrla.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2expuhlif.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsdwhxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdearrj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnymrmj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkoykst.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzmwaxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkdzun.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdphhzyo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbthcxkt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbapomq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2saipdsod.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvonojs.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzyjsld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvrflhv.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwflonwq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyipykui.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwilycap.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzysggjw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xufddhxg.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfjrqk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmviwsr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bnihntpf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqypigaj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiccdnd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oatnmiuj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyqgdjo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpkdzbs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aguzjhnm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2egehmscv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2osrfhvxk.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhnjjio.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szhhceog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2faglqmpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkxmwnr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozidhcsw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkchuli.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyslboul.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnccoujb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pttfuljf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxmrayl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2iosetagq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhyclkz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvuvtqe.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbezrrys.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2enryehzo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwzfwer.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2rsixetwo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfklfsug.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjxbrjs.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiicvmw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlyokvb.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjtktef.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2enxpfqpl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlmfswy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprzhcw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yunkamql.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2noeekkcx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjaujm.html


<!-- 参考信息 -->