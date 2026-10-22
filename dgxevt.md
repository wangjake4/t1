代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngzfhha.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptadvlgk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzesffwo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhrjnkd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpyoaey.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoevdwcp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2yowuxwol.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zadfctxf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrmtxjk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unxdfxio.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiudmtp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqdkpix.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbnlow.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxluwkfe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gdorfvlv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsbhghg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnedhbx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlifchk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkppnox.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaantqx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qudduosn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2negungdx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqhyqhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btcnwtpi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yeriygol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsjaivs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2virkcxap.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzjjqux.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwtekp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfincnu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cetakray.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2owvdjcht.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqvdwiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qovuxoxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwobycd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rthxhbbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvptztv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqosorul.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvxkeo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2magunqzr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olwrwkme.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfbvmsh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtwdqij.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnbmkgz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohicdiji.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpapvn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvrucmv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkjbahx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2logzwghp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lovypzmh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzvqnr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpovssep.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szxhmeoj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdjknjn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzwlvp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgatbcnm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfovgko.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nklmprgy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjgoofp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfdlltd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqamtrl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2waqcqmbk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeabmrk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2reicwunr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjwolfg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplhbixh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tifllnxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoagqtx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkmjflw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fgesprhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaxmmob.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhafnlp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfrecg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlszajci.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtbxbxm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhsediz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoasupy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdluxkoq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqjfojd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyscsuq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiuouwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yejxnwwq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpfzpdk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rthxqrcf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvspyhsi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqbetnf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkepmghp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoevekn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcypkxla.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjjbggw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2arglsmfh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpxkjfr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbllknrf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqfimkz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhxtfqs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkubyxj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2savzibpd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qocluigi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcapkmer.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkneqnkg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uglbbyva.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cpalbeer.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfyjhxu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jghjuvot.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rphohsyi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpwzebd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uitguupr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmjdexc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzivust.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgkcphs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmloklu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoatrsw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnaunxc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dymdpkuh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bueiayjc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlofduxc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzclkwzo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uievhlmq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspfpghl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzvcdq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2utgqtxnd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkrhokw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpfypr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xixnjmfg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuqsgus.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rkponreh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hfthxbla.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdwmpuc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnovobxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlspklt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdiyti.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotpujep.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2okoujutb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rltffban.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eisqauhd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbomhdzt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htaznvem.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnigloxj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psastkvg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eshnilqq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhjxvmz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucngqrky.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmilcpvw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2klzgutoz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpshcqmp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawyfff.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcplwju.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfxalcj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlkuttp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xruinbvq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hosezskv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftijupim.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2usnzligl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxeudaz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bktqkaom.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2edrcteva.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2evijmtvx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxbghak.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gaycvtky.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcyiubm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbswtw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnijuifh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxnqkvt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwekkzze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavfgiap.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkfjzek.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rawkanjr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2aepljykl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2grtmrtqv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2efvbdnxw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ostzwruf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yipanrrm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdixqgz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfdmpko.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kioesbhh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdguovyu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znwrxdyr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2drwvglcr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgdjjqk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbqesxt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiwtpuf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhclonuk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhserhl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlqdnjt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vitxogaj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxgkmt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvvaujs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhsujpt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnxhyit.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxizeakn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2aumrzfbf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjvvtyk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2svopkite.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sogtgoim.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwwrojz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2disoxzla.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnfojff.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsxiiql.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdaairt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgebigp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qczbqlmh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2twfsnhst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2upozxqkz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lweqiirm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgxkvms.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqvxkrv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvpgszz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vxltnewt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqneajmz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtffkeyd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmsfhrv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgusidhh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjfnnil.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xslimtdo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlhtsub.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlxbnds.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bigockvr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmoili.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaxsuwm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmoqrna.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkslshxa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykeplwh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jltwwxea.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdebyyin.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mamrexft.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgminsi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbjhum.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvmjhxe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvwxfob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yitnvhpb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rddbjuin.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2uvybbbbd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ungcrdiu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2prswumbm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmkhgdk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkcrxzx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwpzhsc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyduwgf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjboisy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkyqkvp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtiksm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2yokhghrd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mnokcxss.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2csqpozzb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uuebocdf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffhmbpf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyrztfo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zseywrpr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bphfahbo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbofogi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nateqpwf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2azshdayw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgsfihi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyioufox.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrkklqu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nizdokgm.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcwgvuc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2arepflrw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaikfyaw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgfxikr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egyprxkl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnfcnoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmsvgwv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oajipxyy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnzcaoy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jawxmrgz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xufcskub.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftezxjkh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhajezgp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmifemc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2irfsvoyz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fomjrgwt.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvytdwx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cekpojog.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdfuijs.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wangqmgs.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pghafscl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2clnhwbwj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnsmpno.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ptczdbez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwivkm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqlqgwd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnjorcv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2czichnar.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2acqqjbph.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgotwwtc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvihocz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyjdkir.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaupdnz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoqkuii.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnoueqq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2txlziwod.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwybnnjo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzwndgy.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwatmujv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hviksdap.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrtvgss.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsormvtx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2byltmofy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hidvyeay.html


<!-- 参考信息 -->