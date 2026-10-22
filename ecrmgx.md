代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysukiwsp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgztdtu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeweknc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiwhqnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsgihmk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2guwdxngt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwcxvwp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eshslfom.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbisjkgu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpmjknv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2htpofmjd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2shaqgutn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2erexvszd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqanfo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2irmwthrp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sckdyste.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexchsvy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiezqgrs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlfhjuu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfjsmbl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvyiuab.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2esppagqb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtzmkrr.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyycsso.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umewwigv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yftsiuhz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfubwksa.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjlcfkj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unysfmjy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klslkecy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijozuhcc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2htbomnyd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqozispz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2caqpmuvo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocedtjik.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpgsoyj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uanlmtpb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvssuwl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsyqqhz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ortzrggg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwtzkvr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wanxcesh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlpjaxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2otqpjeip.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2difodsbv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvkslep.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2irguhxpy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbhqdbr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqirykjo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2edyjmwym.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eegyxckh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2blyfxhfu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyugjtk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcivahhe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdfwaqv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jivjtmoi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvxbndj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdxoqua.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvoctag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhsohnk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eailearn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttamkglt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjbixdf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2feushwmu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2unlkxyvm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptugapkc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2seybrhgu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcheaij.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2langpkpo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzvdnsm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dkudplhk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qncueyak.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oninobzl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lntzikjb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgfqgx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnrspnz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxavham.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cavflvva.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhegwblp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbtgwha.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgenozi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxfdha.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqprpvbk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwacduhc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yisdkctn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwkaxla.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wngagesf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2djxiqppn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sepgjdbk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2djenezyj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhbauiw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptigxetb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbnuctm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oletyyws.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oukwftih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkvdjkz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiklnhy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2obdlwotj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujftxiaa.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyusgho.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmrsjn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2aergyfcc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vugpmxnc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcafrkh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxbapxw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvozmhf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgpjkhs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxprqjf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuvydzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2okvitpjy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2axscnori.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvsrosu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xwayfewe.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrdocz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bokklpik.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaqirde.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfqhrsw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeifmmw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2artyhlms.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pussrmmi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wauyqusm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzshzzm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxddsgeb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmlbbeh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdvsdqx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2olrscosv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2aczcwfrb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2njzylneo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyjzgfc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tjddmldr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2llwvsist.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlxmipp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2knpejlwb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrfcizn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdnbeig.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcftpxv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhaasmq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2seworzwn.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdqyhg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2spqjqlvq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vyahippt.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2digneivs.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaztitw.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xifbyhzh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlwtpfl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkxevzv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfscgey.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjzgagy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2efcffdoy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgkfclm.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njthyqig.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cleojalg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgdjzon.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxftoubo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcgidzq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqvvgpa.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmftwvw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygirtew.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urecqyfl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmmwpjt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejcphts.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhrmror.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfcajjw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2znnhsaln.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzmzrgd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgdorex.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhasfw.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmjlqyv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ktegovjc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqkchih.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgvlcjs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqvryct.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksunbfd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubrnekz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gowynfvt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2axhocffd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzrbovi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2friqnnam.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgpjhek.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbkubir.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqybtx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdzgvod.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsnrtd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvnyddb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzozvvq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyclfza.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2omeoxdqn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pctztmvm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kgthlpzq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkidbwl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yogrxmta.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbtbuhf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvliotb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfesgtvy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovrdaep.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txsruelu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbgzkjt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awrmlslx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2czcklenv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetfgff.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtgtyne.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2svusdjlf.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmwqpmh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2twzsopfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfusywj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsqnkdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glxkyhca.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apbazwzf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2wffouvkg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2suymygzt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2epvnjsaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lekeeyac.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2olfkrezw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqljvf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpsekah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mindmqkd.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsycaco.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dcziwprg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsdeudm.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lehbteog.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrmzuip.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mielvrld.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhnxtvn.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2coytjeli.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2srvtlvav.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlppnot.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hazwalfg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpfmbcf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fchvddjr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdftafp.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsvpsle.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtkyung.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2imifuypw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvxlyhx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2untrfnmh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2smrdzfzj.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvksvxxn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxrjzll.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxcgyex.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbvlevf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxugyjq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldauccst.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcratjj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqniyzh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnjbjrh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzgocki.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnqfvhk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoreehy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2shxpnjrq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvdmnbc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdvhddg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2huhpjtin.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhcgnzg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnbxpgn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqynbfct.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2trypqxqx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2domvxypc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdejqgzn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiurryj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuiuzrb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmndrsk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpqfai.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2inwepyqy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2npjkbsdx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvuhlnh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cirdyskm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmouzgs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgggjpv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpbfebq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpahpzbg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nypraman.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmarqxr.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxokkpr.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqixbvh.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevxtplj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dryuuoca.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rytllgvx.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqiysaj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqjqjvp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hkozudfb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvdqamm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjfttgw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaeaxtc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoxbigv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2borioazu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gayqokwb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfosade.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqvvnrb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgmnxnk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2srgwdjyi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyimbsz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiizoogt.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rahofxtp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfanxpj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2czgjpoqw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxploxin.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2lvetvidk.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imcuzmhz.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2umjnwpkz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyfcddt.html


<!-- 参考信息 -->