代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdxiuzh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2clfmpxux.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhivsqcb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhnnast.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydyjwqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fempctkr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2axyvympd.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehigvnaa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrbmfa.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeysfgv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2msxcruqu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpeqwc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gidbcujb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltadrfym.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2enaznzjg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wgchwcgl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zegbqhuw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rssxhgfc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfitfot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrixhvk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yucsfkyr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwonxcp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrosbxs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iserwyyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmcwmf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjnvaxv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiyuqsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mujykjsy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2srvgrnkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edejwhmy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrlhmpq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwoshce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrkqfwc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kymtcmbc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaycsqm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wusoeuxs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqjlcr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyelbecq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2igpyvkuf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrmlnly.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcznlpk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eupmtopz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkekxbvx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khltpecf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfftiss.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqebiqzf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyehaqat.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyfjugk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzfxgoa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqdiecb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqcnsoi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2tymzjobc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2doluxayv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hithbdol.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewqhzjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzflpwl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgfaejb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfovwkcr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeexbmz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjrhpep.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmajevmp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhpefwq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjibyz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmewrufq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelepzey.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhepnlen.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwbywau.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjycixg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vybzoqtn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaqvtlg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfcmpj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqwdztv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mgevkhcw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2clbjimvg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxnnbqt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2embpvnrf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvynkndg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsuhobb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ytprusxj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnfcpmt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2icgixsel.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsumkvi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xpftvjks.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhjxqnq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2czudlbfa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2itkifydk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmesimnp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgxphht.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsvjbiw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aviryrkp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrurkoxm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dydcndpm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbhgeed.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cubmlqwn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhwkfcg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qypqwzpg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhwqenx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvyrzp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfatuoqr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrontfer.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rltemxtv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsxdtuf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyukzbnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vitihpxg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvszyga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2anxzmuth.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2liotjzob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljlpow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxxtjfm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sigjyiij.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsibtif.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsshohuh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskmzil.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pderdmoz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnrqmrr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxgntx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2elgvjcfy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwlpfla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhgzysy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2irvharlh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhbdcl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2johgzvrd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdqwlx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmghcmef.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeydrsp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjdqbpt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzunnnu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mznqlfjz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlucetvm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxkpdzu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jckurutt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhltoffz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmmqopm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqqazx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfoxivb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjitphbg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iivpiyum.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2thujxecf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvhgwgq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdtqwhi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwvzxvn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwursoa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjoqcu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhqxyy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxqayac.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itcnqenf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okynqsof.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknpwyha.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyiwspq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zikxsqga.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjddbud.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnymtug.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uicbmovb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozryvwpq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzldfpvp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2conwmyhv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2afkgrdkt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcxuogv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhlpho.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxzupz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcbmhan.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2phrvluve.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeslxbz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2obzanyrt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhwbxjz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttarukne.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glohwbxn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpggmljf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkusjurt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpbquqy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqqfikr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtinhfj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cngbjxqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2oapxhiqn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyxihhn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kekwhrgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvwrqaz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2henwzjsj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2speqkgep.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2grdyoxsd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlzkngk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2odyodhnu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkhcien.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxdmhze.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxsfuuz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwjttcb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2sywedjll.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkjbxsz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlwhjoo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbodgeu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2elniimau.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skpbxvoq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mobmecdp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfavewv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmcoihm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yihzqmku.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnftbrdt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2luayhuft.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2whqyjlhf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebficizh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwobayc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqsjvgj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezukugtz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iblntcbj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ossaqpbn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2prkzkeda.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtsehvq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vpijjqkc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoiwmnj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pqebfuxt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2scohgnln.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcomwtq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeffpms.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqetssic.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyhwsgq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitjfdy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvqhqtr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijczyyki.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjttgbco.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dznjgerx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddplubbm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaeuvnq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqfxyhq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqsumfp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooydrwkf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnwmghk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qgedpsvz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjebkfz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2pflbybrh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjkgcdo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmjboye.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdlngaa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozvkhbb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtzglbq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2biwiorpj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpkkmpy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyyacvl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxjjdat.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqrkbbl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxttlgdi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiqubia.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvymzzym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqstead.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfjkmml.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkrgnuw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2snnsdlzf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qvopajfl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkmgca.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfljnvz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlltdki.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpmhoxo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmsxant.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwellkvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odoghise.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nydxhmsr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dluvtsvu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2foyycmfs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drlkpnia.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnmyxep.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgwjful.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwxnpjn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oygvcmei.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwcnkq.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2otdtomhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzaoiwk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmtmnpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhrfeih.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aprnzjux.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jzazlulq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbeenx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsgjgzn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbxobzn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsanzdr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuduxxo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxpkwb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvwglae.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wirljssa.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhfyybo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jolgkkmo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axsdqvhs.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rllyttaj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsorfkip.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klklmkxw.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuqnjhz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuisfkpv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnptdnee.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nywyljyu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uckghdul.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzzndiv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzzjoax.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtxilu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qunjqlvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkdaxwh.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpxogzx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2quzwqfym.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfqfecz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzipntea.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvcngme.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjyxpst.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhdduq.html


<!-- 参考信息 -->