代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2plvnuiab.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbtzwbt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2izyxkmcd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvuhvmy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foawphrf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjfmuff.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hefvmqqu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rrscmyxi.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdsyazy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaoohwk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2trelinfs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrqhsrn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kddxqjkl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwwwxbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgfrncb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjttbpo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cojfarse.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugunbxov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zypxkkkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eajdrhjk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ictsuokd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vczzfbkc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqohzhz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtwufzz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhkearn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2goafvcmt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrkxyxo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2admocvti.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkujamv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qyusgjrt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnpusvf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2erdxhzov.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2slvmsvaa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqddbrnx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgouwont.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzizdyw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wohxrdux.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjgkzbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkcppqt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nelnszvy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwvpahh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdhskln.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltrokj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bshtycyy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jomvgpgz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhibsbk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfmnahr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwenkuwb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdaehba.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtphxjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmunojrn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyxwjbm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyoqhxp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzywiqd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvehtcus.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhhbtx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdixnfrt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaujtpen.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfisyyl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pcltkvgh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbppeyrf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgorsvcw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzmdcym.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbygkyqa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nlinlcwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iabxbagf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqrtxxv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjnfmf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvzyqcc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idzpnuwz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kczecyxx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvgnzvq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qepuywte.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzarixtf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvdjdza.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2iogmvapq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwosgfr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzrjpex.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbowise.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lluizqpt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhmsovf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdcjvo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jniznypu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjilrnj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znhdpojt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsabyin.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aenkmatj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvegwh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxixjxn.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pihrhskk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfctqtvf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqkbtgc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckwqray.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2crndjwza.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdkaejq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkawitz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lotseelj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrfiycp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpdudce.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamnwirz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpenzsfo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bdazeogq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwchezl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtvjleh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwhslqs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drzqtfqb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpbjyge.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmvyckx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzyvhb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mugfpvlj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2okeyhjmf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrsitrb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2impazbgk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnurosef.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oocsgvxc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdehwskw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwnqdkv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrtjkmr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iofspqyl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbbzjra.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cflhauin.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsodmjz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fyivuczz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirjxdka.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qopeluzt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mayyldkt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzvzinq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntecscef.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qawsgsyr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjklqrxq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gusbjplj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zddsmmrk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cscupipy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcukwdk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhyjzso.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbmqmiw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yinvdaxf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwtzqhh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfgwkae.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2feksrtua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmggmerb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpvfdnh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambenptu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbjbstk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgwaoig.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqnmeft.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcatnnv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2esehoyon.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwwevmg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbzulx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbzthpj.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbehdvy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2slsgglwm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfulryb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sadhjrrx.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxcrfdn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfpiyvm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiplbjk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egnmxoio.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfpwxwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrincnw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzznpjl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyynetta.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2whzxfzsc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hezhfvpu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdufncd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgragwza.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsioqkg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesuflak.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwnzqum.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2exobtdsu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhirangk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswjxwut.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wzublmvq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuxppra.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjjqykq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjyzzru.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgauibw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfasamfe.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2iginupih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nirhbxwm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edymenqy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2trpiyucc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkorccku.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxkpdon.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utorvazq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfyqkkm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hyunwrcy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodjhfu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrxxaog.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzarysb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2chbgzwal.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcszqad.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyuvezu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqafkpn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykovlokb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2chznuyyl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2frtojblw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmeingi.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnkswug.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhcqypw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbbrwoa.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeewpuh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjzkomt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwgzmpm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyichpwx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mltvxxsf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjivygbg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfoooei.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rybpgyxm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcnjiun.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcksic.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywsvrmy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cukiaycj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbtndvv.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgvajis.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbjvmly.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsgaxep.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vythnqxh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hglyeaiu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxrmwyj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwekumg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfketwu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoajxgz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2arzrtzlp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vonxwcqi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvhytqr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yesfcuot.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atddevbq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2etmefnom.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbvisb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwllbudb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishmocxt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zklrcnpm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeaacgw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppamrmpf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2elwkkjoe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkrjdga.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqmmjdd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjblzp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpcuntm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeijhmdd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxucqgm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtrwwxq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqgejzy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpkqzvg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntplnhj.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnttcva.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mipyiimz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdfakqu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwncbpju.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoiqvkn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcwyvbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfbvrdt.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlreztg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeylwcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xajxwbka.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nnulmmss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnkxax.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2heskrwur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2blodtnyg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2majfkzqu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zthbxyxh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2odlrkaqa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyimysjf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkilqunf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgakqrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcxpiic.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oaedgspb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxmpxln.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyatnam.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezdxvj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuedgfx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rigfchoq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfgesmf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2atdesurl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnqaxst.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaltvpd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwztexek.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiarevqr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdwhleb.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2inacqjwu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekahhbq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2cspsokss.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxxpndj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwpthou.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2scwoxfdu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocstdk.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ascubtnb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpzypx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cccefnpx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiidncg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsorglv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xplaaoyk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfwijzz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqwhzcz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjiqogg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2juvuxwjv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2deiyhavi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzevbod.html


<!-- 参考信息 -->