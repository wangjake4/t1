代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlnqjxm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frkoxiqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpleceaf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcrgvmc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wfngevdj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivgsfq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmdiigs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fabpbfkt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qicovbfm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbwxwdl.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwuzksa.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cljqtvwh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjhvvs.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjorevdb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gpksiqzi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjaocee.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbnjbis.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfwjvro.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqyhcod.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uaksjqak.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bupbxgel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwwihan.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbapaclm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyzubke.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xakpoztd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhxxwhj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dduekifr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlxugqq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhubmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsgsrjg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pftpsswl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxyycfh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbcsuhk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqltqug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gosvnhqr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2riwfhjwu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rvownqbd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyqnjns.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyntnyfy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nymvnozw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtztdcmh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtdspti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbfkspg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfitrgxd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kondtone.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkwgzyf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bntvaokc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwsgqs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiiinub.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2auweheix.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqhroyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsicsvk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cizvszfv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzpbjue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjeutvj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdyggqg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjctnsy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2udazsgny.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phfabrbs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigowpsn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzltnxzo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dejimdip.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwwvqjf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uykrdhgq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhumjcby.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjpirt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwinuek.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2appmfewh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jphrpizk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhqvunf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2biatxjjb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlulom.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sousvpjo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eselfdzg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnexokz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vguvzuwd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnpwdlb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcezsgev.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmdfvcs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbtoyx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2avtmmxmo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyhhbvr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dutoqmei.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2znedcitl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfecvhdf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2moppoekk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hocribpm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqmetzj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owskjcsl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jogkqvtb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbemxzr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccynpbeh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjracynx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaqilrm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbqzzc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cggaoqri.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yooltkra.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2thhnayhx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeubmqo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2grfufhdp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phitfwoz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkbcrvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzawdwdx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmhdgwx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxpveqf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ammwzxnx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxdokcn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwnkmer.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjavlwei.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlgzphj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbztgyf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkujmen.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuqgqdi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrkhfnx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zymczymf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjrmzfg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrapaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnvaoey.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxwmldr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfrbdi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2apkwzcws.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkvithn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjicyjah.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2euqcgkrl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxljbva.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjizwl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqlwjrh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxkuojt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkajhafh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkksdmgw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnawhngf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjzszmc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwvlach.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2quhlqeeu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyecufao.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzmmwmj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwqmxqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzfisuv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zttuznee.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eywomlbe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dgetxeec.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdulzde.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iknycxte.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2emzktmcy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wltdfecb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjjvpon.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaydsui.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzrnrzy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnymfuj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dengbvmy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrsugpt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2poqswunx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fedfbxew.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhjefx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmfcjga.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbemwrfg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqvndun.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2acxncdph.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmrybra.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2poysdurc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2agsujpto.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdcukmb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yupixppn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiewvsuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcehgze.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnykrire.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlyjfwv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiqboif.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqjfobl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqyyunz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2njnlxiel.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepbddav.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yawziztq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzamxgia.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2olucjtpj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2amuxvkme.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscsywru.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kyezbrhq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfrxjsv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2detvamcd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhrliel.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbaydfu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqylvefg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkyiiii.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2grrjxbgt.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mygrudmx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2abewmagr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eltnujhr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mldrpfos.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2halwnzgs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2miuuqmdd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bokhgfsj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2avlzkrhq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mudbxalf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fxodthpr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgbtljn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpyqkmu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2amrgnefp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvfhlxe.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhmwzvi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fegxkkkz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2afhnyaeo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfjfodl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvqqsqt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ianwpujc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zbupqziu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inbngzik.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wfigmbmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzasrgg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyzddxn.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhifczj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaoztjn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzkluoz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdjzchi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaufnzdl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2udnmhviv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtntikd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyseomd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsstooa.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrqtzcd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmajlcfw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkmwxvu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdsvnaf.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqknvnia.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgifqti.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2idrytxvl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxjkmw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxmptus.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2glyeybis.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwihyjnx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwggjjph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgkfsgt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckomokdm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsrqxpw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvqyqbf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oljaatpu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuhxxle.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhnmcmj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqemolxw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdvsdt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpscxtws.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkbmwu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzyfnto.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wshrsnsl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtbhimz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdrhsdf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlncdnlz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwwxezv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhltghb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebobphc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqeeokm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2scejlvqe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwivvnp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iakdpqvy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2scvafjwp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aufqplsb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepzdpzv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyvkcre.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfyxtsv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iazcrsmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcmlzwm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lspqujsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onuaawqj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bafkkagk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xswvgkcz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srpvlesi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqigptq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kienkinw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2amalhrdh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbncnlam.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qjndxunt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbevzex.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlziruze.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tegifdsb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhkxpjj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzupzrei.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsejquq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2drssnhgh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstgetcm.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nyggjrch.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtrqfwv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomwmhu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsusdyz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvyppaa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwedwdbw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihxyys.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjvpidf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiroqhu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcfyybm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqovszaf.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2fowpqann.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqsremk.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhsbjsb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvesmwu.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtrjmfv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2takiikwe.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bixsazya.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ersyankt.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdryppj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjjddeq.html


<!-- 参考信息 -->