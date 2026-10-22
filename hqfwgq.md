代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzdffnv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bruxwrxe.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslfvjy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2watzulyt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcikqjo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exbiodys.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iarepxxk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzodaiy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpanguh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhmxjz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bpivvube.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdqpmdr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iijifqnh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hndccmik.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jebqmlyk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxsbrea.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdzwlyt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rinzfzlh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcvbvoe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2awrqoaim.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yciwzoct.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2djgofnsw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhhdytw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeoxvis.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2glwppmpu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmzwvap.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlodlwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdawmrwt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrzkyyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjinjflo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrmpswc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2styeeevt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wdswuuuv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdovyfi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsfnbbk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtyzivh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyzmobq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bljhrudw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rayultru.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uobteljf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlcsxfd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2czdqosta.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmksbuec.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdwcemg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjxsvcs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaltnsa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uooviaui.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jffglafk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxffdgi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzijobss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvlngh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gdldnndj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ravgigiu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdbpgrj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgodmtu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfqtmwl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzvczxu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjczhpau.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlrbygl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoowrdqv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcdtolj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sotesodx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmtqmiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhczsh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvxksrs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2inopgfqf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqylwal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxaknrr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kylvsqsv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddanpioo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odygbdzu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2snjheqhi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwwrxpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeywajy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzmazx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2krmzxepz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrsulkb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pscmpcdo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2czbaefzl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrjgrme.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypetxbib.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aboqfhbo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkoajtu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ergghhux.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbekhye.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrggjj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqivsaw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edqidfkx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njqyolsc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnlieck.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhnexim.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvadmari.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdtgbff.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvshrqv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2opdfymov.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqorhdfg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lktinglv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2udyvkjck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnolsvtd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2psaelcsy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxupobs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jedcakio.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2irxvtzcs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbymgfmp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqcvbn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrlnyvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zohrxjze.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbpvyit.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrhuxnz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqizrhh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vizdnuyz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kezaorrk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxowday.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfgnexq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcewxnc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovquomgs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2prtrgqtr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfhwpad.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqllmqkz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnveakg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iawvwghy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qicevyrn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxylxtnc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2skrigzak.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjusggkd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cptlpmtd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibclpqr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhjjoqp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2imwjomnv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcczkxp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbooqhi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaelzxws.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmetapzm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdxolra.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooolrgxw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ictxsupl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxyxetz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeuctcl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yolwwrws.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjqsoo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnipzpj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2salgbbsb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqjgref.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxlmaru.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcytpnb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txjtwzpo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bquyfhuc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jygeqekb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmwigpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtbkwpb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzylkfj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowajlku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsoumgi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2llwtbzzv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdgnydz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpvpepr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvscffb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2irsjwlco.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiacdghf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2arptnhqx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyamqma.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2eynvqnpm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjegqyo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnmbmex.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbrmznu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjnrqfe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybxikze.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kneqfppp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qebttytg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fycviqcx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfirxic.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2nigdxasu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmrikmr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2iadooaws.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujppxrec.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mynffuir.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwzyaug.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoiqazk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqgvrdy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwprggw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbptlwk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgwchrp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpeofxj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkxcpkb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvtiljb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrzgyzd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nghxmyum.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdyschi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwjwhbz.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zexvmxjp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ctygwqgc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uejoychc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2neiakjrw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtkemdo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcceulp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ayanjyqm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsveiyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjaveax.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwtkatp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcobkwfk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2aypbrwbk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyxpzgq.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaklhesl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuijtkf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrxnjqc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kgabvjgx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvccjwon.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eknbduwl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qqznfemu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lolzfbwk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vnumvxkn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vpioodrl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehriiqiv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mchxoygj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrjghfp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvldooq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlypxcxb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvisgol.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjliqvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwprhl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znwwitff.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyanpdw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wddwyirj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2yahrnyid.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsqfocs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ausgjlrr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhmqdeo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2evnsisbn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnizybd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoihvyn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzhyiyq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyxqxhe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmwuypt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqgcjr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhjdnl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwhwysv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyhcbro.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkmgkqf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsfghdt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izdqociw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhglomlg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxooqsvc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqupshzm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhddbcp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqukfec.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2mymdvbkd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2uswipbih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2cutbmuaj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2twheubbm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwhwqwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbpnpxr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcewnbl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzmseyi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nseonqbl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfambru.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yksvgqhc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbirnphd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfopkoua.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgefxzmb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyiycqf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszezvod.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuzaxmq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwuubee.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oonvphis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2polalezm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2swbqfgzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwufyuv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfxowep.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqrjbza.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sizzpznn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoiyxsw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsteghrv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiglvoi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdrejyk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2eldmlgnq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gshqbjty.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtcapir.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pculncln.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwpjapf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2stxkewsb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjswvxx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgdtam.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2joodwjgh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mkitbokv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sydygyyx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfwkzrw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pihdwtcg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfciwrh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxhaitm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lezrybxg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfftmvlg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lvetbxmx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2amqzhdks.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajociqd.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mbljvfda.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuidogc.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvrlfex.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhirksmg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2habufoqv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyqonms.html


<!-- 参考信息 -->