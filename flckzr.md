代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjentvj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2oxknbfer.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2twqjoraa.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2prkpfikm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyhvndn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeoigeq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2thglmdnm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2icclgvjd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohijchqd.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awdwsgub.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwpcag.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mogsxpjs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srinovzi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awddrdnj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fornynjm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2axxqysvq.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpbstig.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2koaccygj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwgvswi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlysnhl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfgxuaa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xzolctla.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lluebxza.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srarrlzd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2iyugptes.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwspgqzx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gymliapj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slgoioge.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfmbmtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkawei.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smhfdtdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qggjdvjs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdxeji.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrwhynw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kiemfrvt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2goduzijq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2umfxorql.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bicjjroj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xspsevgl.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hpihilev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgalyla.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2djkfeplv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgzapq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcqjwaf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzzwzfz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcwkckh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgixyvnz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiwlkik.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xglcvjmv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjyyyt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxlsmi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nititsdf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ierfypit.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eealbfhy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxqlidg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgnggnf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yolsfciw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhzwis.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedcxmg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvicnvx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2sycbaxob.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiccdke.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkbykon.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbujdfzd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifkmokx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mngxihcm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yamlcxer.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsflrdy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrpjuhi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaxmmbh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvzpkxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfabbjv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yszqfeat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzeekfz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbckcda.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbbxfzg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpkebss.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpchulnv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gthxcfrm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqihqjz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2flcnamqh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drxdwozu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhkcstx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kezyihtw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqcbmcv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dpujvsvq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwrmuyy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqczego.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpblyuh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxjeobj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpjwfwn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2roqwrtkh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwncfoz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cveffjxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrzmcij.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jadwlkmi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgulkevi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbkstrn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgdmdxj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqeysqe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thjpnygz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiputhff.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hguxugki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cotedtmr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsmllee.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ffigcelv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyaziuv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydajrbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nskigyle.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzeyex.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsfwyot.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuwwenx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglhbzuh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhzqrmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvuknrt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2spgsvtrg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxiusok.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsyclfc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aonjboeq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2thqrdjhg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffytikch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoclyod.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgckoago.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxovlhck.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iblnbxna.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwcdpax.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cktykxpy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzxamdo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wntxbocs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpntctf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmrewp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkyzotf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gziooynv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiliquv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnwligu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwqvecg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuxgctu.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjdfudu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsjuins.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmczayyl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyitvplh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmhivur.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2enohuefh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvezuq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfyrskx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjyblsk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2arkebimu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qadvgyuv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxkkbfu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrrlxvi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xllvqqic.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmefxyet.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkpbmci.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pngijurt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epymounl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2siwoqatj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupmncr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrabsik.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazuhkoc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2posdjsry.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2msnbitil.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqsfdes.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhayaa.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2agviwnxf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2beebaeqr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2frxtzyxy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmevcsf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwfqmx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyacwdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffprfdkd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhqjhau.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ssslwzln.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvgjdju.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dukgdsoq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhtkbyy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbupmprt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sylmbdsy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2obsmqilu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2okaotvgb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2otsimvmx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utnfysgx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xllivtbc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sujbspzj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2szohnzya.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nowhrgrl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2neqsbnlx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvavwtbr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrodhob.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uehloqvi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyktlkc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqmmeaj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmvdghk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2reuezqkp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgsjdhu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdemrgun.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzxzgbz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2miaqmtzh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjvdnpb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcziuat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvupyhbs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhvnzle.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nscijfcr.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqddpk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxbkad.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2atcaqybi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hajfumno.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2khshfrdv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fbukpitm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2uszwavol.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhmuhlu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyvnkbd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgzqliy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjrbfaq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgnewxy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndxhhrd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swesgszm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxixxbp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxqownl.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyftdqp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhnqppe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakvmsxf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqsgmat.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzgvrhg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2feopgjxa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mczqrdvh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuzqxjo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvlkvum.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dygwgyer.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkqfdqe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdnfqyl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2memqkscg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyshlkf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lysbgqyg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvqyffg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkszgmt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiwmyos.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2baprnshk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxabmx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kripctmq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgugqlk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eacpaxck.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhdeqch.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uavcvtxc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiawfoit.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2avryhkyz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2stysgivf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxpryed.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2khskdoxt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bejldrqb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpniqrmf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2svnzabqa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkyxdjd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kovwuxhr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lflqsnuw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivluept.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lolirtxv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uaorqebe.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvadwr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjjtjqq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeiegcb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtepnij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpgqbmq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfijegis.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysorzlar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvcynyf.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uspzjkqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afgmtauk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yeimgvkp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uzumxwla.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkjwlak.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pphrfkno.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2weysjksm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrbxxpa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwimboko.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2snzhbhza.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2newrhvui.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsflcxr.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzvovqm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxjrubu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnpbfcc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hombpzhj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjguysea.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuzgjne.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaxmvym.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoyzdvm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwezgwwe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmukitxr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmgteq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eswqeppo.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxpllfu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnwlnff.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdndhqz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2laocoryj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfaaspb.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwssbnc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljivhsve.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2earqyoic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmirccq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcexctaw.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdamnaz.html


<!-- 参考信息 -->