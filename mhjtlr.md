代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlotyli.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhgcxh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcpfspu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbjtbwp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nidadmjk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ectmtgft.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmeagb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vttggxgw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqqwdfs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smbsszvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfebapww.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtxxzra.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsibhaqw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeispss.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhhattw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyydzkkh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkikzlmg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yytolsoz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pabgohrq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbleepn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkdfzgm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrputqe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhbbqwo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzluref.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlnfybh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdseltj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wixepecu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwkcgrc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwdfzmq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxmtgbz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaidaosz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mikiwxus.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2sezraavh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odcapzcv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhenhlrc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvsvyfw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnasldwn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2diomaneq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjsxvx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2calttzzw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjaiagd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmosnoy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcifkfv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gafgpdmz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2riltjptf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwyitrk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjhgoy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azyzdfsw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjtyebp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhwazkq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioshkrge.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rempgilv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxnzinf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqafzejo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixrbxue.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gfikkfvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amfyzlac.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyatqcq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimlqvzv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyyisqc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmtghas.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxrcwd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjghdbb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvipqtfu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqpupl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefbzdfm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdirytux.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmgftda.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2peihnwhx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2agaawgwv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mrenufyx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2emihjtda.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2smvffzbn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcirqdq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbnzsix.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hblcfyct.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeyupdk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jbininbt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapwocwn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrnazwq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycujjutr.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeytdlut.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xoviuxwn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkfvphc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbehnhvt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrnxikc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyafrmx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrazihs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkmzrnk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlbfbzw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjavlrnj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaajqwjy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpvtmwe.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcehjfh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzodupbm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgopxiq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhmpdxw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rypypbuk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmruram.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsjpuwf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dckrfbkl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2algwnrmn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2waptmttm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttoxlcs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzyfvtx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkqfgyz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfoapym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiufvor.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciosbfht.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwqtgsh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxivdldr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfpdsup.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkpyca.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpahpri.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wucctelb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yikpjovc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iypbrvan.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxgzcaz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hscpdfab.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkejnvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gvesbnoo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfkkcau.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2baizrrrs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2awiabcoi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkjoftp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhzunrm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdnwovp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qclknvnr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kovgjqdh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2slvrnpgo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uysndxpg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvswegf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbivmvmz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bblxljcv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmejnlw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfrpvwu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgqiih.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmcuajx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdszkegq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcljqecf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddccpmzf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrizlkw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkffftfp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxumngi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avmjjggh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrjojvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaafkko.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydathjbj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2sobpsbkb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpqbjw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgokyav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwrysqq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuextji.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fysgutkd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbqmgln.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwmhfws.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdevwh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncvsjv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hauetmet.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2paqgzsur.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xllooqlm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zneddgxv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaqkzpn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzqicip.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2efbcomai.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2himxfxhq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eccypeub.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mfotnoiz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcslgfzj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjqdxqt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqatkxg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfpntlk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihdhkfk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oczlcrfj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2iytfwzvr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhegrvp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnordkf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2luyfkghx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2goevmihc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxjoeyv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbroyoms.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2owwnherd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myjaxyzu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oclvmnrh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpnjycz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vdreoarv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwelksi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvxgvcs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sbadrpju.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzjadpf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqomqbal.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfviuaht.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2twhpsbea.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2byaajqvj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rratxmxo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyomrjl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzjpdfs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtphsvf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2tibytpgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zywppgpj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxuovy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyscbznt.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawmzpy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcibih.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvlvscb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsylerlu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlahrh.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqwfqor.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvobhkz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbkpfg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqatmbm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxmzqmi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2eylosjgl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwcwfvk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrznwqn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2idhxbftt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiakchaz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byjnktfd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yutxaxcv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvhcrxd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2filrvmkd.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqqcyfc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxflleaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjigymwm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2flxfzbmd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmomurwe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bssuguly.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcufgou.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eectzghm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcioyvvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pyocwezo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwczzdp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlwvros.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmkkdaj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgiytf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsolsgmp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzjgdvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnppetnj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2radnjlbe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzbteqf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2palfxjlq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clpofdig.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzmipqo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpujrbe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzloiqli.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpsiori.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzodkhey.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkcqelo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzoabz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehinurff.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgfzbap.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpopxnho.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhygoa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bygoierg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdczpvx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziricoqp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qizgbqev.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvvrkjr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpukcro.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2voxbgxlg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ormweelz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkqjwai.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvoysyo.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjewmyhw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxpyevz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyisgmt.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbbbkkn.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoidify.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrotiup.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2majbtnad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdcgikv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgivauy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jrshxxov.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2waccutmh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzniwk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiafzovo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhxlmdq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwezsxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2izaxmrrj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkvgovf.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lurxpufz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdzkcmw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdvbybk.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnymjsb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhmwesv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gumjturc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzytogbb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqessff.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjbvcbt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2makvhpfm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgebgufs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwxckxt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgtzhiu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkblput.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgyixnu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ynblxtuj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwozpswz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxuyuwd.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qphkrzcm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzflia.html


<!-- 参考信息 -->