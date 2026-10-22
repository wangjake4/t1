代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyibrlri.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecwnzh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqvjcn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwutcyhx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svyywyyo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pghfmfyu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgammyjq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbnbpzk.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yswksjjj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyopzya.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqzxfk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cytvovtx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcnervm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omyrcgkn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2adndbknc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfteftbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhvebrp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zonosofr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2sotwdxxi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzvrsae.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeupxjbq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvbgwov.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2orvzowcm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhuhuht.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjztjlu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrausbj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2osrrfokv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mufihgim.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmvnzak.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyoumje.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtktdir.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfhbmkf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ldongkel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsmscwn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vantcjmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbscbjf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtewbdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqizltjs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iketixfv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rqppkplj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtoounv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjtfzi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsdznkt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqvolpf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mockpezo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2flnzzwoy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwyspxw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxrsfnq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jfehclap.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjjqcr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abesssuo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2enizzebt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqmobvj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhitamh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmnhndn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bugybxbn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkbffjl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmgbybo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pisfqrnb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtjuejs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iktcxemm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2axeuzanx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvpepql.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgfsyep.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtujqzq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sndwkyhs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwowkccp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjjjusk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcedsukx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oryydhxu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhbdbby.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggqyukp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqendjt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acshncce.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgwchfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2aghoqoed.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaabfugo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmtpszo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2velzhocx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmohagfa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bnljpdvl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnebhlo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2enopgqku.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qetgazxd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vamrdtxd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlefgvs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2teltmsif.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqciihdy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wuonfusb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abigvece.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnhfwgu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsxpwyy.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tihtwijp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyyjepp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbleaibk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmkzldn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaicqpv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrmpmx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsbffin.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaygdia.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anafqhgq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykusvmxh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwbnwc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzauqnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qamjuxgm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkwvrxd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2giakvhju.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yemrplne.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqcjvfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaspbut.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqymfbvj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfqofkp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkyxciw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyoqtfe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnihxmur.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fseqhqjz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpazvab.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiznonx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrscsmix.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkauqidq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2flasomud.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozngkkw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvnbxeh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qolvzszp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sgntfzyk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmaowwu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdmqpxd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrjwpbm.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2etpnzskq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2thdzmlzr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrgldic.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzojpesn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuqpamw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nonakveg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebambmln.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhrixjo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwmskpp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eajssqzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2udglstnv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlyrjic.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfqopgr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2luldmhls.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvzcdlh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepajtlb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jumgvtry.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgssufm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2thphjdfp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2clrdiazs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgqcxwm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqbcqvp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsvlzxx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dblctpue.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhsawug.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2quuujlmg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zczdqgfd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwaoxjt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2msuyywhl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvegwser.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtrhmoa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkkqmmg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppusuhtf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oermxggp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoivecjb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2niklzwbq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qtinblan.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2satbscek.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kphsspju.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrdllfk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhwipfz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcozlbq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkiuvpz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2onaalsff.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njbgsonc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdwieqn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzybcqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwuqhk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oddngamg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2msunwcml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrwduc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rqynlyod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dszskyeh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sunfrnbs.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyknctv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrmixx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnytslt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbuvyrn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bupqzfco.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcobxbmj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqcuzfp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxinwei.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2iapqazur.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsejuxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwgscnr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeyiord.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbmqtmq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uscvuzub.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxacoerq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvxkkiu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2orhrgkbl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyfmcoc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzqcsms.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2deimscpm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjqjjfh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xccnzddn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlidamc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpkmlzb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2exthzxsi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsreiid.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxrdqdd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgijcxrz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevarnb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjaztnf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2celuvdft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqccusb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2onkdsyao.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbobhuwf.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2aryplqqo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2affguemv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmleclp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxuvbpx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2esbaaakw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbyivta.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvifcfj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstlhsis.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsywhjf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvshuetu.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xirsnfxa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjssak.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqolicl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjwrxqi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrvnbmm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmizeu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwixwrjn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhtrkir.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfezjxi.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kflugiqx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgebwtc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whnklkbt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhybntx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpyzher.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cunoegav.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gplbrrif.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcpfrzo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2bxifjsyu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmgqeof.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlovzlo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2okcucshe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrarhfi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnqmxwm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxwjbmg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlixkvtm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jewlqoyf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2loizmefr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcdwusn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2plqrbkwd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2izrwdjcr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2imyiekzq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybbxgrs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnyxtxk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qolzrljh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxmnaab.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ectobafh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnojogl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhhzwcz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddelxogu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwpovmo.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdroipb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrnjvuu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttirveyz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlgmzhc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuyfmpr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbugpwuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyaonon.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hapezvgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfasajbk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwxhnq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpouvic.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2euusdblv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcshgru.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2clajpmdr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxwnwhi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xglghhar.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2cveriujr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqoypoj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpqrats.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpbylcl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvofksbc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpzcene.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2icilnaab.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhewftnl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzijeyeg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyzaymu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxzelra.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uozdhpia.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nneduhnf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxrmzxx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggvydsh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjzutsx.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbxlmy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmsdywz.html


<!-- 参考信息 -->