代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2odkitoyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrgehfe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjilrdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yywxxfkq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamkjar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbmzzkl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmfzodm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyyfbib.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqzibka.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmldgj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzhmoes.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfmqvuz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2aizxmkyg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjcewej.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hispmibh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlblepc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzaztjf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2badavvmw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuydzqc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2llbhqplx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edgipgqu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtfikpr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2piwjxlxr.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbufemdf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wdypyrnv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmdjbjr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axttgxme.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhcdotg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqqtskj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wspffyxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukukvja.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lufekmve.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2egxdyfjy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtbqiea.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2twybbdeh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpdwgdt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxnydow.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgitdsax.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiquwyyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2whatinxj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjccspva.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2djewbgod.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsxlesk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxcajrs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bquwjxwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fckfheyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljdsalu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjkwwou.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgtkdrh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdsdzda.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavpmwgr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enalxxxa.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dooyihkj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqniskhu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfluvcw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwhhdpk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtteaof.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpgdysm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pduzhrdy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vndiyqek.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pltockau.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xivithto.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwfhmhm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjjqemr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2znjgijsw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kphwprqw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sicjrxjy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvsomze.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpybevqo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbklouv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vifqwwxq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelrwwug.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqhixo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwkdncj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtunkcrn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxajefp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbipeax.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmdkmgt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjxdyol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrshlhg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxmvpif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjtuiow.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaevurd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtaqley.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpvsuiy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2owocwjki.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpbszsj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmekray.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyizrybd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozafokj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgepxfct.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eauwngxi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uykqzrzp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtwyvf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sddwlurl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrvocrz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqakedg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxaphc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlqsce.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfymrlpj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdvdxpt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbnhito.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjlryin.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2khbgosak.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwsaby.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ympokrou.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzbtbel.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfohuzw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawnurva.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2awovxomw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvyicuf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzkvit.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgatlpbo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaejizgm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hofeqmuc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmykspcn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvceqmf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vschkzqz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnllkfm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxyjtae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhxeuwf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmhfoj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdjnpaw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2cllamqvw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvphmv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlznzdzk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfjtaea.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnifinim.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltghnnzv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhknycrq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkoris.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmpgnmf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rftdanug.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfhaede.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhtdjhn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxpgrei.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmdcuxv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2aatayyaf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2jeirlmaf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vorbeadp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eskhqftd.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfndeaeq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oncmmbaw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2youaqprx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjzznpj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybnkxay.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wstgcfig.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rebhvkvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mihaamai.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhikdvba.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tekvclwe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egukvatm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbtmvme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvlzfjw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjgocar.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdftnnri.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwsnmpt.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iakzsvvz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xctnkrcr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqlxsvz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrcafgh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgcaeig.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqqvasx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yabmckga.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnfbiur.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbobga.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gzodehma.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxhdlie.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2njtxbiqo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaelhf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfqcdm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxsubzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2puodnqfe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmhemwl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2sqflmbze.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawdniex.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdikkvr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxtokjg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uojmkubr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tymmrtxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyalfth.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pigxorko.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2txqxkjwf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoayypt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfcdjmx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfczwpu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkckzjnx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hymnoqte.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfuswer.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iapaoahh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdttocw.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybiztlm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceedsows.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgwnusg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnkrcnn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2yahrnbca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djakavak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlptqgr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwstnl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvbrcxq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxroqhvc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvhksmn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmzohv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzypqyfy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2anutikgy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuwhnkn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdidord.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vurpfali.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuexjbfj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2clssnski.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcsaqaz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2woacrwyt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2susmjhww.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdboizs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2takcyhbm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsmeyon.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtfwfij.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbtwlcy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwhekmg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpnxruz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqrofub.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmuitut.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kxumthsg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeinhfx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjlmjxi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbvsqw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxbztcv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydexjffv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dioxsior.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlpkkuw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozyvuag.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ultkbyrn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyryrxkg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjytvzwm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcrjdcl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoidbu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiilbyeb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzqrkfs.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmxfzc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmijkycq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhorpcm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjulvjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yewkmtar.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etgxzvyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfdllcz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fumsvfee.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xahyygqb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gflubbws.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtseiapg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpakiqy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2litembql.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkngettd.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llzlhdan.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqgzdxq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdgnuf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cppbekjm.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymugzmjq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhinwhpp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeihpvw.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ouulumhz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqssimo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zoymwhjk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uttuhdnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqldqhkg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksthngfd.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyivpxmc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfvqio.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ovezmjis.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsywbdo.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxvbtds.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2vrenapvw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2elmzvhxf.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouufnaqd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrmvgud.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqkaqj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibqwnz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdlhejt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2omgoonpc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdvqtsa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnkhgce.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2diuvbjql.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2npybjnso.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfyjtct.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtsqonh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoxnqaj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwhqnnp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2coffmhwy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2euoiyxwg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqmrgsg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udqppjnk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcertldu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jprtmati.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvenyow.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyirpnp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaiwflm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2atbcibjx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmoqvia.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2btkkvhsy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2gfylkfif.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcozsyf.html


<!-- 参考信息 -->