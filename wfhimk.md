代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibizxhug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmmlna.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpaxaws.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2buujknwx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdowcjvm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sneahelg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqftngn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqmfhlz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcczmev.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjpbcfm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwpbxui.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tniujalb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmlqnsu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwwxfph.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkmsjpx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfgyhrn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2quzuadox.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eerhipcd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hivpldzr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwcfrrf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jgextngr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uhctivvd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpkppym.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjtouyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpfpupz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrncbgie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvfxmtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btfvlbkd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgocowv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkdptpy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwhbsib.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cwchbshe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xaftcbil.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhchmwur.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrbjxyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsliabw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgevjlzc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2odygsngp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2conzhmro.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxpfyet.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlwguyc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmclqbm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwekdna.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efatggqp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdychqkp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjuuhji.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeooqud.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvzlpqu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znttclhb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvnrioo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqhtunw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzxlzfi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwxixnf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2klqeigbc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemivkf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzofkgm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbjeygw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyvwfqo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfxfxb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnsqdpb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqjbdwh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuldksi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxzvjum.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbbhcgd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgbvkwy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbuxzos.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgxcfem.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxqwdfs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqghftnp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvktbsgc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2otsansvo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdaaqr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2buimsybi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qxegfehz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2obxykqka.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atcvrgrk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahedrvsq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fanquigm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2klylcsqe.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xntujonq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmfeyae.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twfjetxi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bumcymrk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2teyxurck.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzkmkbp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfyxwov.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjofcax.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpcqlkk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2egomptjc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxysulg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cygaenye.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xakdtrfn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtgzlzv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbqwuku.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatjcfcs.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfufuxa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcsxpxx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xixahytp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxtarbt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzradzhz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkbmgqb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkeypvh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgicya.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvgdsng.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypisbc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsfuqka.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtgammr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yamuzoiy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nanazaax.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqzacln.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyvdtxs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2quctxeei.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdituiiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiqemld.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2oidldzqy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2woxdbuaf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcmwqlz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvptnwa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxjweoy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpuzvbj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaeqqba.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2fubmhydp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurwsfeh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2flsqutpi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbocmmg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2slrnvlvk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujrtfdt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jdprvhhq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzlqevj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2poihyntt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlibisv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydglocp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpghjagf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabrgmed.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggrwtv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owcmmrob.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djkqozpr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2khtbhwpl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmfftsc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuglvpu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyswzpqw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixocobdg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxkyfmr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2baqlxsmz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyjfcwn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tloknuqe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2abkzqomn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjkoxk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2chaovkgj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pysoieqw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsbzzna.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaueohqi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmivrfdw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sranvlan.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqhevfx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2osocybeg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaccgst.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zheaivul.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkcrcgd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqnycv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrwtcmw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvejzqn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwkkfxp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gtykdetz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoujxks.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbdyskb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxotdvs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkqhzrh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqwgsfb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwnwjaf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vixijedm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzyoxj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnkrzzr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkjikog.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2humvatjv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfxukfm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzipwrc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpljbbt.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprjjblu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxstuyh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2obyxaxge.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjotloj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqkugwz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhddrcqk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eytubaya.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fspxhauf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kauqmimc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpprjupt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvlugex.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rejivbsd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2adpolclv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uacrpspv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyatpxvo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2umyzbrfi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwsgrve.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vuimgddx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtkjhfa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpxpszv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvzwejs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzwjoju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpqfgsy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2boyesxkx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntpfioq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozvzqmi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trhpsemz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fdliwysf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbewyvtd.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfoiuxp.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmdkmvr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pafhcenl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgswxtts.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzttzhy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlukdcn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgbdyex.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaddlpp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uygolrgh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrnlkxk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2heibtioe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztdgsfj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghionycp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrzbqaq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvxvjg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2supobrud.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvijnqy.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jayrwzrl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnqbdei.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jymynlnm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypojuupk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhwmfep.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwspkku.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwwscpk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbiggos.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuezxeod.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdwenkg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wckqbqfu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeljizk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgkayug.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qnedyqta.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmfmvot.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcbimcv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjpdowo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyxpxhe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsnqsve.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sppjxiba.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioscgvmo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyxtwtc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwpornj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcyzbzh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnatkln.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgmesao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavvyerc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzptfdwm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dazjhznb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyltpsz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjsnsju.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2myvztzyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eghdtokm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jopttozl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2shejaooc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvpata.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vakfiibj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hstsssal.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuetimh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nirnwrwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjfvbho.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsqfqwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rupkzecj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjorcnp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gpocjqgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwanzfh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2houxamoj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgzgqky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqqpka.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxacdunj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2kycrfogs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmcideh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcdyckz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2onjktaij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wufupmeg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikcqiqh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtespcju.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsikfkds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfirtpfd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2odrrdggr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmfrddi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlcekil.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtizokk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eewiptyr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjiotvh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgqpryg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiyhusm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2saugxzut.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uucxqjhu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedfgsn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cehyxrid.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fskfxmzb.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2batxmugm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2csozqrdq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oarotxym.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqomfaik.html


<!-- 参考信息 -->