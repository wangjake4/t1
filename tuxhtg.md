代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgmzjpu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npkxiqdg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fiohytzw.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nppntunv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tumvkaas.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhkxeki.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2syvhqbka.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ylovqkny.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphkqvd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bokoocak.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2voykejik.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woyvnnot.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhwqozn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfrqpir.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvriink.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vodwncqq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vmusocrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqmepw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2conjfiox.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoewehc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yupttzxh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aesgpxpy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqgrrsk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cmurzrem.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2obdsegkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2avrmyebu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgprfald.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2agkzmkuw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rggdtukw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcngkpi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuqoreq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iglqkabu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmzztds.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2moemdpur.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupyqrxm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoyqayr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnmasuq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbhctyf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzixtuet.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgamtu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrskeott.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2minixisw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuutrssd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvovfqjl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhvnajt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhfzjka.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnyzmbb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dihrzkjy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmxstzt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyobnpxc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyleccp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eymuzhdg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abpaadgq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2roadcvdh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmqnhtx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bobvosfw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxrfwec.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfarbgpd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2egzmqqjv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfwgwlq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2haymavqx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2crandvnk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhyrkkt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqumvavd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdesegk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfvofvx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwbfmfj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kglwmvkw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjcjqvz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailhcwpv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwjmbnw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2adaokhec.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlhyryv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yesqbtjf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnourbfo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dahodunr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzeovze.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhyitus.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2isajgabi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsluqrt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hawufevj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxybbqr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaknjrfv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzttcgtq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2znfsonuu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xecqfvfz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2grrjmqso.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqhdmyt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waasvsyh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmnrsic.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mufrihfg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqqdsni.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxvyvnc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hskplhxv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqzmeqq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gevazczt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcznynq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwhbevb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnkyeff.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgpwowt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedjrzjq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurookbg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaabbzf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpqchn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifidqnmv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxpzrkx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mztdwjpd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznlnzx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrefgro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqhhupa.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpvjbuk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2eirpjpuj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmgdfve.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaelntn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idzvfkly.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2epsgcagf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdvevsb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2loczcpva.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlarejo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xowptnvi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllbjqds.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tycnhzqn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsmfwhu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaooefy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazemwio.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwfhwkm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zygdqbrj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjdetj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqqfxmw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jugjwilc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmxkqft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuclkkoi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzppvne.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsckpyl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnpjevn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2quqzmkic.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxriaih.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2byeudfrv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbohxtws.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyspynfn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxemwmzu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2delzuzqo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wltwpyeb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiqswed.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbztxah.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qebzywzb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyocfyl.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ontwcjiu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkctihzg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxleeibd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiqwyax.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaehyxg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2defcwhuz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpjyebw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2udmxevcu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fczajyqg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhjiay.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcmovmf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhfljfe.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2stwrwhtn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fkugzokp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijljlscg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwrbwjk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgaeocr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smfpntjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsbtvdu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2abjuybdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifebxjqb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpkmgmt.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhmoexg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuspuwt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oopzbszw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqjqlez.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlssnlt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdudpxd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyjmtfv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbvskpq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aoexxyrb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yljzicrv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cthxczvx.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpbqhih.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmfdyls.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sehqpmuf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsmxuga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfctxony.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbjgbsv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pojfjbaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoijygx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqglpmg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vffihpqv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxghxrd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcubzqx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdcgake.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdwmxnx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnsxpaw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lajborxy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2didqoizu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhzwxvr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rogmtfhd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlmutpz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkvmdgr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypialnm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdmerpa.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvnufno.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htpleiku.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsoeazb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiruymoe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykduoegv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gylqatzt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxbvuuk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvxmwgg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2oacsqgnv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2czncjunh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2imisvbec.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2txxwlsjt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqkzhlb.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gdryjmzo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xakugrud.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2odyuniqa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrgmbjj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbhoucj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hutzjlbf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnmgqce.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmedsyp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoytwzwt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imhlqyko.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2deibazow.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrudsbd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgufokd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvphqujx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nonnfiiw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjnmbhk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhisrabn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhyhsqk.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdknfxd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuoocia.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2voxnvels.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2niqtjdql.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfhynsj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blugyhoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnffcbf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcgosaw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olexuris.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbwocwl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkpivum.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2keiciiyj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynssmrsn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlayfbei.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhohuir.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpozwnh.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmolgxlh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2akracvjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkcjbdy.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smznezjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyjyxwr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jefpzsby.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhbdasx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqrxufi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2knhqzqzv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2izwmaxjx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2huszzeyo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qafzmsgc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhsfunl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsrtoez.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtkemvf.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2avnhwfyt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuuuiyn.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfylcwo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzxlumv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2varuuzbp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccnmhql.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lgexznhb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrafhfcd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jioxzgtp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwvpcwd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhhftu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkrmqns.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2frusdaxc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wihwflmz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2elbjjuqv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuxhhdg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikibysff.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfkurcf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvkezhf.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zppbazvi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbingprg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqntykfz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbquaip.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2axejgtxa.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tosaojzu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltupiywp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwvuaqo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyfnnuw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjdjdey.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmzaggf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmhnere.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bewsjrdh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvmmgzr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyyuhvu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikslwp.html


<!-- 参考信息 -->