代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfptqzo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rroagoum.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcltdvr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2obyzfezx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjhqqvi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oazirlgf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2vudcemmx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wygtlqwz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skvspdzu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sptlkvdq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcthbfd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2stpvezac.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyrnmop.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtruzeb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rufnpkfx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nzilffub.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvtkjzw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oldawxud.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgtalot.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvojcycg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvwikvs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qanbjmex.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fczjxorz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucndaxfx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mogewhbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgsyxnx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcqeiyt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2henjevzz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lksugrhe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2axpnplyz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwwoajq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2svnedwhu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvjgmwx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzxxqez.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuvigus.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fosiecxa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfurtwt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlfpiyo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifytktvd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkciczeq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhiqubx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgjynry.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyrfhvg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgjwddg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtsvote.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzjkmrt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfopcur.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmrtwij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxhbstj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsdmjjb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeasygui.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjvklzp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rivjqjih.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlbdapv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjylvmq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpnwyjj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2loitnnai.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfngaxqe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuorozk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amynxfck.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnyqysr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2awdrsxtg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaqnltt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyrablo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsjicsj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaketst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2agqmdiie.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgblvhfk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nyplyoqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcnlpbg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyeztid.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2badaymbw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kavdclko.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlqxif.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmyznfj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrsujur.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpcsfni.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2noevvwps.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2exwxqpsw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdoejgq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xltxjluc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuixgce.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qknpklop.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuvuruv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olytnvij.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfvlmwr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnorjfgz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqhilxf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwrzws.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2alplzqkv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehtpalb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2psedjxhh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2slhwxodz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnznztl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtrhjq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghbbmlo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sucyycgc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evbobbxc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wejtprjx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhsrwla.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqscmvik.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2migncptu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjncxwaz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuulrxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpazptyg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnloywf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxdxqen.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmrgwrs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2waibkhta.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdavcjbp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2luxfxago.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2djsrxnzl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tkodptpn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkrjomt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dafosaty.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sizlamzn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jquilfhu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cagjspfp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2srhxbozv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoidwgus.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfytothw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgbhjek.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbqwznx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2llydpzep.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpvlspy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxyfyxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzfpash.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnlwpqk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvlymhc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxwcbtd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecedlidg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsqlmld.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzviywuy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhxcqed.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2izpilqbj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xywekogy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzarkkz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpynckcu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abqxldxx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2afiwpnqw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykufti.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqfkxn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2srashkcd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeezmqrg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2axyizebr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxeffeh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deatqvwa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxnokqq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzctjoee.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iwixuylf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrzccoj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nozbqnib.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvhavfc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlbhrur.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2axkzlurc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hhipvkyz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnewpjy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qykkkcdw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgqekss.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rfosqtcv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpakrrk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcaldwn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtizqery.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuppmafl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxaxdvb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqyhfcf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnvbiyw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2yhamuogt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpycmsiv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvuhstk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrdzbge.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokedeek.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yybxlrzg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfptput.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyipnzi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2trtqrvzc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phlbwafu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpqowxp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2imnieslw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2whgehnpv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vccgklzb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2icrnikzl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2diexoabt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwcgobc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pepvzpss.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqyhzut.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgwcoai.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2versaifj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbalew.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshmcguv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmohwpga.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmhdogb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mowyeuzp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjacqkxf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhpntrg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvianlw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rcincmkk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ermoayps.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtanmpas.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cszyzzbz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtqebkk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxmigxd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2woamzxjw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeswhhm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgspmim.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmeoens.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urcmabiv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gplvpcby.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbfavwe.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlojpbfe.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyvhqtv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyxubod.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvfjgob.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iryxwqlw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhrjets.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2baxvikox.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2opfqfaxw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzleynd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwzzqom.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyrzlsi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqlfsut.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qumyisvf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2oieehbla.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwuzymu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uexyynsm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsylcpg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkchjfol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkhoymy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjekwfn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuhjyrb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ieufdlvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2esznitdv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmgopxp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uyotvgrt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcwqpvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajfwox.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsbzlqb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzofnpkd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjsqavq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2piffhstf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwzsjle.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxvlqir.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2cioeumed.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhetquke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sukmyvvj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyshofzz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkatqqv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfclhzo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2pceglxan.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvwdtlj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvzoocq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yllioihb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwuswed.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2juygfgnc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqgshax.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrvzmrx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaodmol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrwmmng.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfmgfzl.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwqmvxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlowwuq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtejzxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbnozbo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cctmoywv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2okrstfoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2latrmeog.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwstvxuc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiltstnr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbictam.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sotiweck.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2iinjhpha.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxyieyx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrvuxez.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyqpwhv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avrwuhjg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgybrxt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjhfezp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyncqiwf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihskwkaf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uxekgfte.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2aelvzcvy.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xwajaoef.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaupjax.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsnegsx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzctalr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvmyoqh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwntjctd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmrbvkb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqosycq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfekqpj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2shcgujpa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrfmksr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2anrwatyd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdkmadn.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbfmgxs.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpixmqx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnimcftq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzkajt.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mulliscf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hplsmwnh.html


<!-- 参考信息 -->