代发 wailian999

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeylxwd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgftwdr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxeutah.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guuibmww.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmugfep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkttxff.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdggceux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiivsts.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2elivobka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucstlhhh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfckjknb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zuijpyhb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijjgif.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2igsysmln.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2orxnbfpz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflhygc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuxmnio.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nofotkih.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2arspxsxg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rvddtdgt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnopwbl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsytlbc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucdntb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtczffy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmutigdf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeehjypm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuivamp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpebucvn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwlnqi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedlbled.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnyfytr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2amemotwn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjlbvig.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemwyymq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmslcdhw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnykbgy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdmlrky.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcdqpww.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvynztj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtljfsw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yesvetjc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqovaas.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqugkiow.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nipeacfb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbolorhp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sguqnccl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fiemnnzw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2btmlkmir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritqonbm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbukheo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhuqzsw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwwnnpy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfsxpkf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsrxocj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvzevn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmllaxm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrfrmfg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2syfsfcas.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2epggplwa.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qdinycjz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2spxgbhut.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnocoio.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrgewvk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2skcasnkv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzwytow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxchmcv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lifsiwse.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwwlbtj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nztvscfh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytymdfro.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxefdhw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2psqezkhq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psebqjck.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnlismv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vreufapz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mviymshw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyddkcsu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnmogcy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2anogdmuc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtddzjdu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpaidqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzopohg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxizbsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfllohr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrznuxz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfdlhse.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwsroyr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymccarze.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxumpqo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2geovyjbt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2noegfdxi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvulbdd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcisopw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsbklui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeoblzw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtdhdti.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwbcxzd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2aeesqvlz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpuxtby.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiyoblt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrapbxc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoaomtw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhjxypo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2urupdhpn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdtslel.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhkzvvg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolgqtpf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpmonr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gndtzuaj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gfymphxv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fpolduwy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxltpex.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjknxscf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhirgrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxoflb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icvlsfdo.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvszhxa.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjxquzr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpuezvx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hipulgpl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2roqkolie.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeobhwmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaahkkyu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2edxfadyc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bcglpmmw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epxtgbfv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqguyibi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjilelx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzcepco.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqagjded.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goomnone.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shmcjlyj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeqkyss.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtfwivz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzccrm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbelzqch.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mjklvnig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpztjomn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfestolp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjvnod.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexsfxx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsrdfua.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2hyejdqrt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzxgtln.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkayqzi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2harawyqq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wneyxjsd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvyafwe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbphdyec.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdayfbk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hayjngad.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tvreafqg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2obbfyuaq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwduvqar.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhldhol.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzjszcd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgweuqz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzkmvan.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iucqevnt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2skzowkpa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgsarnp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2cldftykr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxbfcpb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxvakmy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkyrwgh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhftgvuy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zufudxco.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbfunif.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2toenmqxe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvuagr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rteuihyv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2askczccc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zyizqvyd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqactkys.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwohygfy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2cavlulqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkphrtqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzcqiai.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxhiktv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdgkgdx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdadnwh.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhqjfkc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgyuejs.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2blstzplm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjnbyix.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pysecfnc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzxhegu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2afjkotlm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vncghrbt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqtotg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dmndekdv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcfrpo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gujjrvio.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmegyiod.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpivucoj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhilenh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgipuux.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdrsul.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckcmly.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aztsbidc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upkjetqv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ppciiihr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euojbimn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2uocrjvwh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrafaen.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqshdcv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpjqfao.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfmdvrm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xqosfqyc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2altyqkhu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jebsjzfh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewsaylw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gunwhzvf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfsoufo.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsltvez.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmmwjve.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eruemjev.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcnosuk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuvyiiy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbayisjk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijohcfh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwqckgu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfdjpvv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2riliwxna.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2exyzalyf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjzzuzu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrphws.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2plfijknz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2earjuftk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikwzrgy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxqzjjv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgjoglm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmjnxjn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crojemua.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjhsyrl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmmwnol.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvhwyno.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfauridg.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vagvwgvy.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2baqnmoax.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsxyvdk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgnjuu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffakeqwm.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nttouliu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzfasdd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltllvafd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmlobmc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrxunnc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfirflg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffhfwmu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzectsh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjmexqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbtpykh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2weyvprhn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfwefli.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvmvxee.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnhijuy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxrbtps.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstzhcgh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcksirnj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvxukuk.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhrzljs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fakhtcsu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcbmgk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2defpmtsr.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmkthao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssasnznn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrunctw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsutrbrk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuoxwqi.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqfhvcx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2luspthsf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnayoqf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2einrssdw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvffsom.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmstogk.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlevahqb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2odbwwacs.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgaobsn.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwrjcmv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpepiwys.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiljokq.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2attzctun.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sgztsuwe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2imsliqld.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2chjqxqlc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsunjsew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oirsprnt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yewxczvg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pignfeki.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyyifnc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxluwkz.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrwyqv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rejgpghc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvioojjp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwfzekq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnhtakd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaydjmo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkayrll.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjqxemt.html


<!-- 参考信息 -->