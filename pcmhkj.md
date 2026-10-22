代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhneztjx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzqfltf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmtwmpx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zewwcnat.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdijrdm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuqbrtw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjohzka.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2apicqoxe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrlmuti.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acdkgxlx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmxsnrs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbaywbd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfitirsn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tesntjmg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnzarzp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2azolnhjr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjbwktx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdouycp.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlczjnk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nysskurg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2suhdoujf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjjqyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwgtbwn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usjzpgfr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nchjgyqt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gctbdgdb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emvilxef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfheroyw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2djpnylrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slxrbeax.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxjjnje.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2anzllpwi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrjhqkx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmwvurw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfatgsd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ynalnplx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2asxgitmj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjkxznq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfcjdo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pevnfrzm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgodpc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgegzlx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xukfylty.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtupkol.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilolcwny.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgbunbw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eixgmygm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tquytfkp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eoheyybh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvjbxfb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtxmjcf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2afixmtwt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmptrgj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkwqjgs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2umpbtgue.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufyznr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tagogfkd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkiaigo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqthbbn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdxdlfx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnjuyee.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsenabs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcpsxtl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eustnocb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yybaclnl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqcnqxg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsghilu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2upwghvml.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlvegis.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqoombo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmbvpyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfktshi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sgleulsh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvurdld.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjiaqoz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnrmasd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkzhvfx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cekntltm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2slksrrsf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ardtqwxd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dawnuifq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmhschx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhulgel.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmyvyfl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2obipjlic.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjricn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtzwtsf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgsdgov.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gavqhxfc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uklrudoc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2smnjxfxc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvaogtl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpimmclf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2llpknvjs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisrfipn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctboqiuq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrncqsu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2btqyyauq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiorbzk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2htcsxnkm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozinumlq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zswlfglw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxywfqvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddefbwox.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2inawdwyj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uczdefxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2llgnjlzo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjhrioi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhhaacc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qldcafek.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmltzent.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2btdhrzhl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbelsfzh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmwuivw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwvzgms.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxirmger.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2grzvjokt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsvjjk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zckbivbv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwaxod.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtufpav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qequylqv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwsfii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2arzimtce.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbcbqpx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlarqyx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arezzswc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qtruzyon.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyxllgn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dszyrqux.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ecshbwmf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqtxoun.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rosoccyl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2syaduoqr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmaoppn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbxhoru.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtekelsh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dggqudcu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkbkvbl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsihqfh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgwpgrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkmmef.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjvgjwa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zewkoeuf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2aagqcgoz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mklyjmjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eilkdjup.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtrkygu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkejyfvw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkooynnq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvmanem.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtjrzay.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwtudq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcppwksb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmzninv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2twwhxoyw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dqszcarb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuwnbpx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gygxirqf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tetmddxt.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlnybkv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfyrcob.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2mccvfnmi.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2yvraypfn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlsmkqm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbptnypr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnnkrks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcuzkfs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgclmul.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fltixwny.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kslxkhxu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2auesctrx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zmphiutp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcumysep.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aingqfse.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiuvflo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbugylhk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvgycow.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgenfol.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqewjvm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwztqer.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkomidi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzrnojq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oilkxmaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2maxndmwm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjaqojr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrpfhmk.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnqfchj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjidoigq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzojtnzy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgkvwgt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqmyosg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjkiwt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmmloqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2scvvbmdh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjwxfhy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmtghka.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vevbylvh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhplxld.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcohynqt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2owtoxpjf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyxkhhm.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsodlkg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeqzpbq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2llfyxtgl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cbierzps.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tclixmrw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2txcvzsdy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvipiqj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpnxnud.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mksozple.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbduksq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpldikrv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmiorzj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoefrdx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdyezqg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2arnjfxah.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqadsaeb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2smaoknrd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaudkyi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upwxymxe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wajrlfmq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbfqwrq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2xplxelsl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmzbygp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofhnugb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxnnnff.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoaphuv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqdnghs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcylxbqh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuyfunb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzbnvee.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2baoznhkh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2njngezhk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qlocpxjg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhwhekh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspyrqup.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyaqhys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wekobjni.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cktmnmcr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhkfot.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxuvedz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2phzmkvkq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnywgubp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucjtgff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2irgerxhu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsjfne.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaewzaim.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzoaczo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvldbus.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxzniqr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzkhslu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2izekjkjr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khonuudl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymcvhzu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzjjakl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoczlsx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwvwmge.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvhybll.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2serjsidz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbruehh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wguskvdd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlfinbb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhmvymm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhblxkd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2albwxfrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blwxqjuf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szakgsvp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgrkpjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aahzyrpy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zauwwphm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpgynak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2auiiggua.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lryarvve.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zdffpfhk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxhgywb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwusdmeb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xjznvyhj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtpmarg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupzaxos.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vingdfcp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymirtdw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvvakgh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qbngknua.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jorpqffl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhqpjbq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qncgrlmr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxyalri.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmzcgsg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkaeifd.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pugzwnjl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2eikjensi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kizwgwcr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjlkqoa.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcxpczn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajksfsr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vohfkabc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiykzkx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqobbdi.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpshbit.html


<!-- 参考信息 -->