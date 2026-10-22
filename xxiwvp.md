代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apijuxlk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2agpysapy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtwpcgk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2znevoylp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsurllvd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2odfzjnpo.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiupnto.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtknfos.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsobnefj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhgcvk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeslnnr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmscjtgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2weouytzc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idrsbaug.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvsuoej.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2klcjsfxp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnerkgbf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lisktzhd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nrruafet.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2obqrklgo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gvslmnma.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2weioggub.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiapiys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sfffrefo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xosdtrnp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jagjhpzy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jsocxthp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzvlnub.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgbntzh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaixitpb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oetayrtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzxmpiu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgiedih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vergcxul.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcppxlj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2obqpscvt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqxsjhp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdomxwvn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrihkkd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiividv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwbegri.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2atbriade.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwywsjor.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rrztjtoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuxsdrx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfhsmes.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdzpcwp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhuhmer.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhlsjs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pteyvdwx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjztps.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighzniez.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ergpodrd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuiwcem.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykleznyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2actbfwqq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnhejpy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtyhjhx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dskczlyw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyozunaa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmmbvj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2twcpbbmz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluuutkq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tplijgvp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytqlxr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmsgrl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwklpbky.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpcudbb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqshpipc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmafdtmy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqrnclo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nssjioyl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsaaefg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2orpnmmap.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnfjibm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkspidaf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoghzhh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iijebmyh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmyihbh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvdgrow.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwykqxc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadwzilt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnuheen.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jcusgxfz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2osnhlijl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrfrogq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aoautgdi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbjuamx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlrjjpr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqoyxa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlobync.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljksstfo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpwseon.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvknsm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vryexkoy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrhvdhj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmaunga.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpgosgi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uduatyuf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2akvuwriv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcidxyb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzclxje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqqsvgz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmexqlu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrdoefv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nynmwguz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nftkfgla.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcuxiyj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkpsalq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjmpyag.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zprznnjl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyytoccm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2appndurj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khudeqel.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyqqosf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqczmmg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bprgnyqu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdtvgqt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbaacco.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmjrdpo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fikqdheo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwumtite.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaexzpcz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2grcupwok.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fntdvtxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpzkhc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkaiwjl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nolntrfq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdgpudr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsltfnv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsqugqf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjnpsfc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eplwjnpf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjhfxvt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjmymvm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdayrchl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawypcec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxmvksu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbgqmtc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhpkqjg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewxdura.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2umjuydou.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxhzmb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2feueyvqn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccknpsvf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzyseov.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmsossj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2doeynohs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2knthdrsq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntedaeyl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqqoqeg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qncmavav.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2erxgdnpn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xykbkxth.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqkcpib.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbhomkp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxdetua.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2impgpbum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuosbrq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmifuyb.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjeqaml.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkqigez.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsdmqdx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hexlgqpc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpicvyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2shavcgxn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ookigiit.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxtusim.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akwhwtny.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2abcemfwq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgofyav.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chcxizlc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojpnbbh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiotlsc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrbwcaw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2urbjafnl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacupwr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2glddcguy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuxbjjy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdacbjtl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtktxnte.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vweelkvj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pewdzphu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjwzkhq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyfvveu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2eggvxlto.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlyajir.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zsddzacg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqnxdfr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaloyws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpyipsy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgaizrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2upjluskx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2knyhkgfn.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyzcgrs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpzkxt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tocndqeq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbitgg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfsusug.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2whaymwbw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcektbpt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gubstamx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qxucjqbb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptvmsg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2toqsclkl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2grimnzph.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehbghjg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2axumtdsr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfhhvtz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxirwsd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybigyujl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvsfltx.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2tewdvdld.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2uiczjhua.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gozwzuet.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2arnmtubh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgwbkhk.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvexwzo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhnspkc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmljcgdi.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2badmojem.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkvhexq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lynuaqne.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitanwmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtnjbgg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzqgcdl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rinjmhkb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqztsek.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wghsdwrs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wplibywp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcwlezp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhqzadh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqguixp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkedvz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2punoaxil.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nraxmzxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdimvjeb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2egbjymxg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cieyqflp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcecjw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2httahwwh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcvtdnt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2udmhobqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoovyro.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvwacrw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtxqmeh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuggeevr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpdpgot.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dksftegi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvivyiae.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bkooozab.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2notadtpq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xefvnrhg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkkqwwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjswgso.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pepckdfy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2efizptyl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulxkspp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlzmds.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxusmoa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcmhkdj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsivtwo.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbbfoed.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2euyjosmo.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxlztq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsovbfve.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgmzknr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwqfogb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbqhqip.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vunovqtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxttblkq.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxrcioj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2fouqanni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsvpkon.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwpqltl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2orqzyrqa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cupahqih.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubujxbvf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwkofdc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmqspnh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2konedepw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvhsoti.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjulpvzk.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeinnstr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzjvxmo.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfvktqb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xedkvwhe.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcfkvm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pslzegyi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwphlyqc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aonesjpn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbuwcvv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zugvzcyk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuonee.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2twetrfng.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2sttxyair.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyazyeio.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcvvte.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbxewif.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhbybg.html


<!-- 参考信息 -->