代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2opixjbsl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqofxtsu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpqknx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrkkfij.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2srewysgs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxclmmyj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tehkiejv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpipoyrk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgbuiq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vriofmik.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjbsuzm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qywukmot.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prcpmiof.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvflikln.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krpczhlq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvelwbc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrlayrz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wznqmucj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrofkym.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimqlfro.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jutwrmxp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymydsite.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtoiqgx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpglini.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxifznx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yowgizih.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pawphhot.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppibgzb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgruoqm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcwpezx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzajyvnf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2divgylbp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdtxtzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsezxipe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfegroro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmakhbm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxjowsb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsrrmnm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eujhsmnq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2faclqdac.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihemrzg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuleljxn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqderce.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsszvzgg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbggtnmm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqdvki.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tchfxvuy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2upxehuof.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzkeapi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrxipeu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycduqvqi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjtqihv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wboxbtxz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiykgbyx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2usktqsap.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyugvncf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2injnmlnz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiwlwjt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdvnhid.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbmehpi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpqseok.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2syqpjpbp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubszypgh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2npnagxlb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaabamc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxxuwcy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhmwvvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjzjiyg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqxaszx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dlanwres.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpmehkg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtcwih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozktjuvr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhfanwc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssexyvlj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2juhzbqnq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrpwqkf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpyahmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwmmnms.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkngiipg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kszlcfux.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2roggobsy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyxlkzb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ywubnylv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqifyfxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfftxyz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggmgkjh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsdveeo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2noiptvya.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivzublx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuaihqb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsjamoo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2khqgskmk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbwueel.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2blfupaxs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cirtcdyd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewchcdxv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpupuyvx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2teegrfps.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orcurefz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipayiayr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eejiajpw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2oetshsao.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2exljeqxc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekrtuni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwrajys.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsgfjbw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfhuhwy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zomnhaoq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpuuqfi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbmrrph.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhzxjdp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjqwbql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxmgbej.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnklbsy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzyowse.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2modmdszs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzxkqyp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmumfqf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcxdydc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkypxwi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vevgzziy.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwunaqc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgavuvl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmpkmeu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiutefc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rabammkx.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpmmykl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbdtiss.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkipbctt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbgiyzc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqwyqle.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihzenmr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yakfikfq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhktcei.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kngneeri.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2idihyume.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2haskoqce.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cylxydwh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqhhild.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2etrhhoyd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tteokapf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yichqnrk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2owxswgwa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvhhfty.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcklomw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2snpjkott.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwmejew.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsybfeg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2esmzmaym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuxqxuu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyrootb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gadipeys.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oeevfjzx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2aphdjoff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoxbgow.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkkijru.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tauphkge.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kygpbkts.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2spgkxxar.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmapqix.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2relbfwmr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2muzpbphq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2svwruemc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxadfqbx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2forynisr.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegovfxl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkegnrj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nufhbatj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nidchbqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2aooywzlz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrclwii.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxxwtz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2imkgmtpg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hbppjkjl.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2epafvywl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdmsrav.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiskhlaf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvzipge.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmzfzjw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgshpkf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyckjwv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiejyvap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2seglsjug.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnczifse.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gabcghhy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjabuyav.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbskwls.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2litrmeeq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2igisfmbg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmucdqc.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmsqgnm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnqpio.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjuusju.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzxbyhk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftutmmv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhkjwn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnukrtv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdypawig.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuydbxw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmdkrfl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamdmqm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqbncgv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvnzstr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovzyghy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naeneloi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvavmdgk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jggeqpvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaettolf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrnrwgj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwmpbjn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwcsafp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dggxzzxk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpozikz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjmwjyl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnrhsoa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixebzexj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tajvejob.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuyqdql.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvjmhcg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yidwyygm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyioajwu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhmtgiv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyhlsgd.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhaspq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfnfykr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuflgpz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmtamia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnvqqsj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlykskd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boqrjguj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2birjlchs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2eddhoubp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwijpyzn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gchubjzt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunrtif.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aometyux.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhgrmme.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtcshuv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnoxben.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkpjqsh.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rokwdezc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvyuflu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhszxbap.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqgbfqg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgueppkx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpaxfmw.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvkatzg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2btkpzlyt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lthjipka.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2smvtrhkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbokkcr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbklpst.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2drrfawmh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxsjmjx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnzzdvw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzshesqc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2clboetat.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbvlvmv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bplqsaiq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pprnyxis.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2avlaoseq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmosxnax.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiqsnuh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofamadrn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnihcmc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoizefci.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtghrov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2isuotgje.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdgvmtd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2galalmtb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbcwecb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2znsupdox.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iypwidbp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmobmacc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jayonngp.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ormytsjj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiyxyvi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwuadzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aainhbyd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpztujol.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgmrreb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuekgtnu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpfcokm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyokaywd.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2utulmcfw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2naleagap.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfrgzem.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydyjkhr.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtckqgs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqofsoh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuftwsl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gastimgn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2eneqpqco.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2egiyuukk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqjvpeh.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbtbxza.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pysmpboe.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpzkqsq.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmtcgzb.html


<!-- 参考信息 -->