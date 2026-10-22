代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknwxaof.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eecwzpzv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2saplveyq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2brzbdvqg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxqupf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owadmnho.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmqvbon.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuvilxi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crwtvowd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbeucmd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eevchuko.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2axaamfon.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqhnpem.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2endyyprz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqpnhxm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmlewen.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbitmcm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhrvnxv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wirhkgfq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcceampg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoiffaz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgkjeix.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usiexdnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnxckct.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikbavs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvoaxgo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2skvsguai.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gtraazbj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdxfunt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqjjqhg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqbdvb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mynzqbqt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzrzpdz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2scwkarco.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvxkts.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuxfjws.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2teqzfwen.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2amcfegvx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeapjnn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwiujbr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuawdcf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozkbaeo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbldrkb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjyadsn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwnzusz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jobkqrff.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skujkemr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2szbsrpwm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtemfove.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2llnapzvd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhgcwxf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tawmnclr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuczizx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pswcmeuu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlaxfmq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefuwtpj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2uifcpzdg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cidqldsk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiywhppr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnqktwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ardqiysw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfedkiwi.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pciozhbo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhayirz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyrhdwi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmxstqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuyeout.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuwgmon.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqvcqox.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mgulyhlv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbccwypz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smdhgjqc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2subesfck.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbyavab.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyfgbie.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpttovx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gerctwee.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnjicsy.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbucgfb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczdtmww.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2weppzcaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2flhmrpjv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrigxfrt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcprlry.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaodylq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhlhvqi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2docybffq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mknynzeb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdvtipm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxvsag.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoppzvfo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsezagx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnxsnyw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxcihzo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvhhbxm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2utprnlsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2soffutkt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxzbpeq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxrwmgo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbogwtu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvsiyml.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gicummrg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2eocjmjue.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpayhad.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqdhjhy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zazooegt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ismszbvb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2slyneyly.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekftuhcx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssourevs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzmzgqo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktkcfzs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnxbzo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmywvbi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcajyok.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdtvwv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wipybdiw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnlgspc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpthyhs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmygzgim.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyznfof.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpzuqfd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaakagb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wewcfxvi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2whogxgzt.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kebhnurz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aeimciiy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myzbxdeb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfgwudj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvzgnon.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivytejbt.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgajzwx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoibhsx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoglkgoh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2iebumbsw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyftksnu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeybaczg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivazzlik.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrenidpa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ociqbejo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dlirwcws.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvklxdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpdeykl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dflhjdsv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lecqhgyw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnihxip.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2teijgzih.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsdcfhq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxoosdr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrtasre.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqznpxy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2szspilcs.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wwglbfpw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2abilybqe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgygdsv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2arliphqv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eeekulsy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlmgpxw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2thyzxpqe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fthaycfk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2orevkinu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gziobxgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrliylr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbousln.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfzcpss.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstxhcfm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeffbvf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zibndjuh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqjlqog.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnidldv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqclywrg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnunejz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuvcibg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bisegnkt.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbqzgwi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwubbgv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djswqdvb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzbwtqz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmigaxd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emjzpzyc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxekiud.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2blnrtsvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkizemtw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeayodl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uowuunni.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tielybjh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwasmeq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwmdloi.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nomcbrxx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiswctg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2udwaemet.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqhtpgb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2okguzvqs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzjlrjy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcmczot.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvssbrb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2tshkftiu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfauokv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkxgtxd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lugrarpu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhnbaxj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2udfsamyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpuyjzv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqnfokg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mujluana.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2znvzsyzl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpelvws.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qofreykj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfvxpfa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dviuqjif.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eueidigc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyloymfc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmiopbl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffztiiej.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxhxgec.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzexjnj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeipkvz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxeljsz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqbzyka.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaumqay.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnovglc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaafcaj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadufcg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkuehwu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcqvida.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhdaegs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mamagqqb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyljuge.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjrqvum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxnllvj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eovirreu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfwbhnm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qouickac.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgysalj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzzktae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnzgvml.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzbqxld.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhwfxdr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwqztxj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aamhgyoo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtdnyuc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2syqmdmrw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfrqoiu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkzhxtr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoqvlvb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpmlgwd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaaroce.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxqszc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhindrmf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqktnln.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvoaom.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtuflvy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vplxyeyh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2abgiorzg.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrpypfb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2immbcphc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyjkznz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gitmduwn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtvycgg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyigcifg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcvtzmd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pangvgem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuyeuuj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpofgbk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2wzutnzrw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oagtcswv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhtptbz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnxvpby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkhobwk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2grnlcdai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2grfmdxov.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkdveva.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gogciqqw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nakfwvnb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfijvhh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlqmuam.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2laqvtrpp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvxqlo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2erugrjge.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpnneib.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qodvtftz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqvczcw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzrtmok.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvifdof.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfdwajv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsdinob.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmgiicj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ekocnnej.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxnwola.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhtcvmc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbbrgmd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fowisktx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zizsgiec.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdnlthr.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aipccrfd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqqczbl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lidngxxf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2udwqpeti.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zozwdtms.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdesqnk.html


<!-- 参考信息 -->