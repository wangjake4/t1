代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbuctap.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2syhulakv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrqcexe.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csuotylu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhntdrsr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjxulxx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbebqjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrzjxef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eujrwqzh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pglxngxv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrmsuxf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmqmkpd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxqjhse.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lkorbunx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsymkrn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtejdvc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hedfnexx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwewdrw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmruxnrm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsruijxv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2istaydxr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grhgmoqc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiprxpi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jibnewmb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeetudn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpcmcmf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkoqcye.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzmeziz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnsjorl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2exhsrlmz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrphxtuw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2coaofusy.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzufysbf.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbnsbxw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbssryz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2laqfrnom.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsawoyz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeblacg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrotnji.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2unqvgjkk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mososvet.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2halbhxtv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdifovg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2daecrjrs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaktqrs.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsimmof.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmndkot.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlngfxii.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sisfzksa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmuvdqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdmxayu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnmprwp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukypghso.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqepwhb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmqgkjm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgjkmnf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmzpycb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxxmbid.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzymyugp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzytuwzg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mygncoca.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2shutudxi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bymazmse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzglvtv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbefmfgp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mivumhvh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bagolvlt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaairlvt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnqphwv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epbxkepz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2boldrrjf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfwfpxa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdrlkjr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmcmxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oatdaikp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xnofwkvb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcgivaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmqfjgz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyndcngj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvueuwp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrqbbm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2syuwtlxn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egexvjba.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2niuzvwpb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyllhnd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fypvouex.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvcfaei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjafcqbr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwwqick.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxyqrnf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2isbizhbu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxeazy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrxdkiq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzilebg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukasba.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2scunfsle.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkswtcl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkuzft.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2scsxwohe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2munpycuh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxbbwah.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrzudbf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsrpkmk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpihrliw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qckunaxe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoitmocd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scwdfzvn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhpqmtk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoqnyvu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2woeivqnp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kakauwua.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzczcave.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uumizoqk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2byayegbb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbzrkc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuyixnm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrvwdae.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzkfoo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2fsanszcc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrnvdil.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdqpjot.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hoybhkla.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdzfksh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2isdyqwnr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieylflkn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2taasnfil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2djzrizwf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2diqgzhyj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjpnzzh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2byibfpzk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2abklapqe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsrwprr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2seoeurcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkykzvfe.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiktihi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmqtlld.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcspvih.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoqruid.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtjuhye.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zuihljtp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbvdfgs.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjggfuq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnbguur.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkntjlh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbmcfi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eciruspw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nweikmui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2poenvbrd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrtjajb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhvghy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdutdwxk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrfmtzv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuievbw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqexzafr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxcdvu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbxfqcc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqsnenc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlavgecs.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2itzijpjz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvwrhqz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2spkllslp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lemsiayl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkvjuot.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpqvoor.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxbwktj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rozbgvpv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnzdhmw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrgrcv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qascxhkv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anasdqrl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqwbexo.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdivorn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojbljmr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atvhhpaq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbliphx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mduademl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqaqnco.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqsqigc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxqcrww.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcrtzu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvlhtb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyewtkap.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvkdtxg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcizrnlz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2awmixvmt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wizgowlz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbetuybi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjpvrdi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2koubpvnd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2excitsdn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbawuxh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvwxiig.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbimcwee.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wokzhpcf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxlafic.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgnthdb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bztftmju.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rilkthfq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsksgap.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzunsvl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2icykdejj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gboluban.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2iuterlsf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpubpvn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwvjoea.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrtecpt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxypewps.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzfhvfm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lortljra.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnwxrch.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaytqax.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuuxpar.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2njizyscx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2adllizwe.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsdqifa.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyrgzng.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmtwiip.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kealpjnx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaojeiiw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2baijfkec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iovnfdes.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqrraix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mepunqit.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbllsi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxipuw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbdmrg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ealqodgt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrusgbli.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tecjkhdi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlgxpby.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkcgvnv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyzsbw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxdcfcw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2asvqjlly.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwswbfrj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyotxhyt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jclbsikn.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjtytoc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfojtvpq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vduxjnbu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsnkymu.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yshnnvqw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqbkmv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhaagrq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuslzmrs.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaznhux.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrswvfh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tipxcuid.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxedkpwa.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmwubjh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfjwrto.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukobphct.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwillil.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffioaero.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cthhwbwo.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwpvdnv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdgjnqf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjwbbdx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eikgvdcp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2emhciktm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2phxobkuk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkfczbc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzwmbew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyclofe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nemrhzvn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbspyxx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdizkag.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfntmtgc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyljkgef.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcpyjd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvbqamk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hznxgcrr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgonmsm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pngsfpoe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clihiuoo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtktppfz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxrrgsj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsrdprq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zixuafij.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyigbuu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibilkkh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2otdbnzuh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gurznuzx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfgoswj.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuuoyei.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqiqbjq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2coskhunq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyofeqxt.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqggcpj.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkyhmn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnolthja.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzriibf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2premroim.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pytcowpb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2syydgiwt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvtfukh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjlreul.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdmplcr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsweseok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwddxm.html


<!-- 参考信息 -->