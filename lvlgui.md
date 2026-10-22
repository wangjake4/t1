代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhztdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oufkwaix.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibclshrm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxxmikl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfpsqeg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2loicbpyc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbemhfkg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2grcwthtm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwvktsq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyqmcmq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bglnlmqp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mmodygyg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2usilgqib.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sczangbo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cywhuora.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtaybbx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dywrqhsx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhizvwmn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhwdoai.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mghukemj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsmtjzl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaushdtr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqluwyky.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpwkfik.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqabrphs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapkycd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvbiouj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzivrhq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzioacpq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmanmgq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoqdgak.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xigkqcyt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2oopvrnav.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2krhqaxos.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izpclbln.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqndlsie.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxavcxj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcwiueg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rasmubch.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sddrkhgh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2boennqrh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsdebwn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvjctuh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxwbeig.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcwxceb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sysxveqw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhcejjs.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bepcjpyt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgsanmu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2siohquyp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dagrsacl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltlgve.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxifztvh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizrojnh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxrmccs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrovypse.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iualtuvd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsmetrx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkxeidw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mahmzjbd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuorkuo.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdjktiq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmovqeop.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxirvwxv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzichvtu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uscdxlsx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvmznfw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxeobra.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfhqzxv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnljnuh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdziewob.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyffycnx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjubpqu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmqesli.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaheemez.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oikmsbhy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhndcd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cblnlwlx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijrsdab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjthzxm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmlaaiq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvsfzjh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nflohhvb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmvuqcc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnkwczr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsvjxwc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vznkufau.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbcdpmd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xirrgkzi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdwzyid.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwosoayp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpljrtn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbzusoh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcjdgig.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qryfrmav.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2onjtsrax.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxigsju.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hytdumfn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2unaleoxz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqsbsdl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjkkrox.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rilslxyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiafjiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhqpmya.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxbihde.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvlzqer.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbphzqw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebmnuka.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjcazbi.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxgslbx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyeqpjk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cviqahnq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rukhtiag.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avtrghnw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfusccnh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hubcejom.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2aiycehbf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkddnty.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyvbrwu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcfpdub.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcqjnnb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aduzrtbk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxwiayc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2beqtflwq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeppuml.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bazthvcv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2plljvets.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojugnzlv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oyanmxmy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2traurqsc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2voftpjyd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpoaxll.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjqazz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgfotqf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2awhcgctw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxvwju.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbhrfmh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wztboivd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2woaykary.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcquuqn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kohheavb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibmtygc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uihegzft.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjotnfi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdolakce.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qidfzmlj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2snuhuewz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhktnjw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxtczm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaqwyap.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uplemmxh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtspvqu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvcsczy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kypkjelj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwfysnr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqpadpt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nugsvucg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dojlfgnk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylvjhs.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxopmue.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxschgus.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2doktzzgi.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyhjpne.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbphxdy.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nomlvazo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsodtdfv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfpodpv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwgpjvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2juredort.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2incgdtpq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uidyztat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2irawnbgn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdtjdsj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhvyjgx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpdrxhb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dabdpkzr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oumwffvk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2syidqswb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqzwccp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hgurlwve.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ahczaqcb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxscfhq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsidbht.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhxykgq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkwfwkv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhgmgjr.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgsnwks.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggoqxpf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysleaxod.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igoensmg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxehlcg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2iecwkhvn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtpgbef.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsnsiyf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhfedqc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbweoift.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkxhku.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2slgpwgxb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnwlksd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxedigm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gbspdprs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nabjogjk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzqfzix.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2caviwhtp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhiehic.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtodniw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhowriv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqfmbbj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewmycwo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mffcfpxx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgrvwgo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tifoghwl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcdpekc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dumqljxc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqfyyyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdrkxwe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2axlmzhse.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uunypckx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kjirohhh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdhnwth.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkjlfw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmotscz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfntsad.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkalyog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yobhunah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtljaced.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggivebz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcruetvt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyakvnkm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txikrasd.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2khuaepro.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdstnpxt.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdtytag.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjjmkh.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmhect.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2edrbkvdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peojrkmt.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odugkvby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdqxosq.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrazpctt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2scpafnni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aujevazn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2decvgdgn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkvvsqv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2omdnawru.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwfoad.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhpvrug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2honxgevm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxfnbpy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hymvaiyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xekbwbmr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cammqxba.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfadwzd.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lruxuwhr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlhcrrd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2siewckmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2icxrlpgm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhecvfwd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2amlxaclm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2srqzhuha.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywodoki.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpvlbiz.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2daryrplz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcinytl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlierjc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2drbimcaz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2deoffpcx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xchxjhpu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2depxqapm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndxubly.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2widbygyz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjliusxm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mccgfcpn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2npixovre.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzivhn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2omhmedym.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdctiwfm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2knhvsrtp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxkoiop.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyznblq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfapqqg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuptttp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjkfyho.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqtfiey.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjtuogq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxdfotx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoikufjq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjuwugy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yngljnzb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2weapuxoh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcrzkza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrahdjb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbplwbxx.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2usxoxzps.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmjwqvn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxpvhne.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgupvlu.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhstypki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxfoki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lupegycf.html


<!-- 参考信息 -->