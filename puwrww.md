代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvyjssq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzbylzt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoddixf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qimjalha.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzamawg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srtxiott.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvhrfeg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtgzdye.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grvaetyi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiifgvgg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqhygla.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2godtlwju.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2niizyqin.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdatiqnb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2manixwrs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2eetaubwe.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnlxmht.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgqtest.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkcsyim.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmpolt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kllrboaz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lofbaznj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qifykcid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmsyod.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2madtdhsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwemsad.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2artsuqlc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbefgnk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2napbfkoi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aahcljol.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjmllju.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwhyngv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hccvotbl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2habichph.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzxibmq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2muyymzhv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2azdulfmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfafsgjw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2znrndxdm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrpkfyw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2livotois.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2djlregrw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoguahq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozvbqkw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfisxto.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxmjbsq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dutaduqw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2oowoiokt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tumkozfo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxkabjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvlovqx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfchliga.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhmwbfv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlfuwfp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgquywzq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgizrafg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bubttrnm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2omgrpdre.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2exgryesv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryluxlhv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcftvco.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgizhvj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcbouwj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbtkxtk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjapwnn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iksfrmqm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbioezk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzvzupl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvlpun.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bswblzyz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2naikpfre.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqylzrgm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2llabtjzs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzclqcpw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2htwlqyqu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tobeznoi.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlszqaxk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlojmfkt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2adyqnbsi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnalibt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ouscvahp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qyddqsgp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaextsl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkaeocm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iznoaqbg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwybthlg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2afprnfhq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpltlrpn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gupdrimg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wluflnub.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnwwuid.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2chjwcuxe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaksbtz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwubtazb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmghzmz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhrfvrm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsihuad.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qshhzyqj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwuurv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ernladmc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bacrhcer.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vehegabd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2egikxeok.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuiqupr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejjgyek.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmcjuaf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkglvyrj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvrypsf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2munofsyu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2doxmtafu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxgkgxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqhpktv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexnaee.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2iroweuao.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvulvxv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2poobvtef.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2acloddie.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzcgbed.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnbiij.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2odzsolie.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wijsmsyi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkggler.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrycjth.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzvgfzc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdslrke.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxxjxbo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2baxuhdmq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtltpgib.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpfxhcw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqsxwzw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieamascd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vliarkkx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yobrpadu.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkoebdu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2phdldldu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mesifojr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tandrrqz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvxnxcd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnfeod.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkyzpvb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsgxcms.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvuztrr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyohmgp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkeclvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpmbxql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiyfrbv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfazgusw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyzdnfu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2irxndqza.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwxktdz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpegvzkp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kunfbgzu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrgtsnu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyebbabe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunqgft.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdhfbvt.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtjbugp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnbznzf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2obygtdab.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2leuavuzq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayswtpdj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvhmpvs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glzlkerk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2elbbbbbo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcsmvdi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpzhyny.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrmaiew.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbgtvon.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ludgtmfo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzbfuwo.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwvdgrz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuzbbbu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgkrbgv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2walzcvsq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zztmhvqt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2acptrtwh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnsyvbx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldoniw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxnvinj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcnoiwd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mquposfl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhbpuvh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvadgwv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uekhmiqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqwjmph.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xrllfhmd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxjvkli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvoscq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2djshstea.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aogjzzxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzsodod.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzjiqmv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkigsrxa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2asuiuhcb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2parefzqa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyyrjkd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlyixlt.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzedhjs.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhurxaom.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyceyrtj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ocznzidx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdalwtk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2freybsym.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2asvtvgbp.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2oknnjwru.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkxtcek.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqubplvk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbtsxdr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwovyjqg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuuwtts.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwkoghj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mviglrnt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypasqdsa.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2youulfzg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpkpvcn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2eskkpghq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjhgtio.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmaimzr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sboaatwx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zezcgbwz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgvadny.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyvbscj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2otnrhnvs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdnasjn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtrmruk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agbbglpp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wscquhpy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnlkapl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhluyfx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2cadakmcv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaiuvho.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fgloeuxs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgezfugd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnkpfrg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclngpp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcvpdkw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqiufr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jalrzgfz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhphtede.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2afbbfuof.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvxxuum.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzcledt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2teeerqiw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2twcvqqeo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qeifntha.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopzoyzw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndotcb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmwpahm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoioaez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccpfgwy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilwjxvq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glsdyrqk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwduyxes.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhgfbhb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2atddeawi.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dogeruik.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwtaxdw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfeqeor.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnbkizk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaetjyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhgvsl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jydirxxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrnkuay.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxydfkna.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2onqzuxoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2najjmmda.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjycbsw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvggkrp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2htqlnqaz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2plsrwxms.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqyblcx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2amkfejas.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knvlmnof.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yixfenib.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyybsyx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnysxhae.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsrutpw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpjkdfn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcgaajv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2regegjza.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2poprwtkn.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lquqijdh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbmyiq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmznjydz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jamwsmhn.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvtdlfb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemqhytm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2sajgpnsz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mprtadis.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxbleaw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2oholjhev.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjerko.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrewevd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqadwioc.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvnxbcg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjligvux.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqicfzr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxihyqa.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2akuirodv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ztucjief.html


<!-- 参考信息 -->