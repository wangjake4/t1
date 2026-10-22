代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuqlfpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaviwdu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlrbkgs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nirpmcld.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qksrtzvn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhweoi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsouoruz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tagpgjhp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqwridd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzzjznd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwetrbn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzixxui.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jaohsgox.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzzfiu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqdest.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwywnegy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywmdgyn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2magqvnua.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsepxvhv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvervnyo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htgxoxuf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsckzdk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhjohm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwwwezk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szhrquja.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvslmehm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuakapj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqndsypb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxdcynh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbukfako.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2midgiemp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yervpdsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiafxnk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkhgxnu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lckcqnld.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvucazzg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hndtmqmb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2waloeivu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcawwhp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavtjuf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjdncdm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqzdxce.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2udiplsao.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfthmqf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaempkm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxghijt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmpcanw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxwegck.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyrvxss.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhukjlyi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swpphebx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vijswqtm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2htghxjpa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvndwmi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqfqyvb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiormlll.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcygpjd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrtcnxo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyggknt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxwyfec.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azppkcqh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyhidgi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlyjrnq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vssmgpro.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdockwz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2owhytwfj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sptwqtda.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnfggzr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2crrkqlpc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2toqtsyjv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpjpnbm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhxpeuy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npoccuun.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuptrtdn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkeimxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwivpqx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2faochngm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bfilayoq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfksiyo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfffysz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtmqoev.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjmhhsn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlonpar.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyfjjcz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwvtzye.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mngiapvw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyhxmqs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnezbhw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iamacmcp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2owdxvbds.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwndsuf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qozbitlp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeekaqz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2unzldise.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjjmcps.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbmyxjx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tstcezny.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyoohyv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrxmgri.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmkmcqh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bghfwoki.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2oppltrbu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hmskkvrc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgodjaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvarjwk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klnrhqph.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ealrwpah.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpvxaav.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvziiigm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wioglvdi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqagygl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqxiokx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqqbmhs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfdospm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhkjbpa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwephwg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2atwvivuz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxreezv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiezacle.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhcvxti.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwgpqsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2imzrtbfn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jguqqovi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jawazvbd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpwqejs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrkzeak.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfryekk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efzqrpto.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrnncde.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbznuadg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrdoksm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhyetna.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwpdhti.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2khrrxwbh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfnjkpv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpwyvnx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdgcang.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ellqtfar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxftljxp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdxzuju.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwokodqy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ittvityr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyntjpjv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2atvobpct.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjlhujx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgobspqu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydctzimc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sptcvyiz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgmfcrb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rahyzvzz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2virkrqup.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bezaapaw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiyrkib.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2srzfrorf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgczyvwa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kymhpccy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tqefgwzj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvpsili.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuateid.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wocfftrv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2edbatqdi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxxldyk.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bbynybhe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uazianec.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkhvlpx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaaakwg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcseotp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqffzfk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pieaoejc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nruxbpfj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uattsbny.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbhvmbj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqmzmy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdowtae.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsdgaym.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovqcwnx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsvgxtw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsubrrf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlzhngb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uonttknv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzozxgp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tevzuxzs.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwrjupm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgvwlus.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvqcwka.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyybigqd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lruzfirl.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqxehix.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uysyufzr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xegcantm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptffaojd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffmjtn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyhqipw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwycusg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsnbuuv.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2apaezfqu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2owhghkxz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2npyaovsi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqksbjp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ladwfoft.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvkbxwi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgikugqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvgeqfi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgcpotb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sskspxye.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcpogdl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2osrrenzr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jcupqdzf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpgqdrt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjlzfc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pguqbuqv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxmfms.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpdtsbt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxptxzu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvjwobd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tohjniry.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwdigen.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmumtwxp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhixysy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcglvxrb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lilkswbc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrtggx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqwhgp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aabzphjg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2debgvjve.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhuhojw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axheiydt.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2suyfzbva.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oivevnaw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqheqdgx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqprcfk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2stiwzdii.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjexmcrb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzafiiy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2usuurthe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimsdbev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zajzdjzr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxgpekj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwmloym.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsugetvs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmidnsdd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzppuild.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeujujen.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrqnpzu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsvaqwx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmyegca.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2htbmcjzo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvjbnzu.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gonmfawj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqhnrxr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyajqjc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbtoqzb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrsuyf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omifnsku.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsjqacq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjvibct.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkhsca.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrkudmv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqdsgra.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2udqxredd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwspgan.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczykmrr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkguxqtz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2colqxlfn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjxgwsz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jujzajkl.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2oisgovro.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2odatknea.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvyoqrg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdztvoyp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwtwlrd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yepkikdx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuvgyvh.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbjzfn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2exduhzrs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjlpauh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoaqybc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvorrbe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbepsdh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoajkln.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2veyauwqs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mceqjvzw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2koyzntxa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkscizrq.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpyhzuo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbppzdm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzxoiis.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsckqyq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszcvvj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlexajt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwsqkvf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2etemkqgg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkuphau.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qssvqryl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcipmbp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbacvle.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmfiosv.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdtkpnz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdjgkoc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjrvxqe.html


<!-- 参考信息 -->