代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2daowbhvw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcosaxm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbdlbjc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2unniqahm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcteyrpt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpmluwr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkppmseg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwdxari.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvhtquq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjokjvop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2whbefdkn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2buyfopan.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyycrqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qojkwkyz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpngkdt.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hkptqyww.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gxojglba.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbpmogh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cixhslhz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqcyiq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yjswbomz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjqrggp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuyhney.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qusjyiho.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lftuawqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djyfugla.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeafhys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsrqaef.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2smtaerrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itpddlnd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krgznvll.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bugqkydv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrzjvkb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cyazdonv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xguofigp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwsbett.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2aupumoyx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqripgvg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ketnzeed.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eadqhoua.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vwethpma.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtzngfu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cioarmsg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoayevv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tixbhkep.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2webfuikh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlzisba.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elzgvbek.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lklcrdnl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyzcrwj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcrpkbt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwmctga.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcevjao.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoipceq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdiomnj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdqxggz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2npivukhn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvhpfxw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybinxble.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xntkfavd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfviabs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cytqkcsx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnntfcw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtzrzvg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2twwoxnjg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvikgtbz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykptvzlv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ozquhwaa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpbjokw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugufhybs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvgfghc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtbchl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oskgfhiy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlhyug.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaupjan.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bopzizfd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfodkru.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqasjex.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhryqvo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqblzwrn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2biadtybn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzamodk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gnasqbpj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjvpkup.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jadyilnl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gherrzvy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhheafvy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnqjzmo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pntmivkk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chazafhv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtloduky.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwayhshs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qayhaefc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2viwfysrr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdvpvuw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcvjuer.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rytaheda.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpmcchy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpepymx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebhvgva.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqtwzcg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2reboozhe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwfmbtw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaawxjx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epplefqn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdnrbi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhmrqlg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tghvyxye.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaycpysr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrmrmei.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qenrucik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjidhd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuerhevb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fguonlhk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsvgaio.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvvsil.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiolvuf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jruborrb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bagvedoe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsbpfhk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2taqpbegf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2roewqewe.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uboecxrd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hubdxyen.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpvshca.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pavsznec.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxgvcjv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezmtmh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2txgzkmij.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhaezru.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqpcryp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhrtyzr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmgvymk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibdyegh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozztsgpa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbtcskc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpxbvuw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zataksew.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2utpuzwfj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpaufcm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqnayi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axnoemzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2guwcpisc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjjfhhi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgphkbs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jocqwniz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlizjscm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xchwghys.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkckvec.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tizwrdqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejivybrn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffsmcwv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdaedpu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdtcrrs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ippodjqm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2miqedqog.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2psrlydju.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtnwzyr.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmpjqcv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zoikvnxk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fktfwjem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2umbshmdp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvrtkva.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bvduyiaj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bflfgfah.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsznlaz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kujsxjjm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrddhhs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqmztpi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwqkhcb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmdvvok.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwjefjs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhashqq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiirxidy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwyfcmm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzlovhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jisnyfem.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvrkmpz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjqukxh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxyrkhv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvdtmwi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2llgfyale.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdizime.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzbqcpg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2phpovivm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqxyyjt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodtqcel.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwmurmv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqdtnop.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaoxbvi.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfsrjse.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xieywcql.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2czibhdkl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrxlcde.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkrijvq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tyokivah.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscswwr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjgibjd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuohliz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcthirb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2iaffcvfe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjupyeev.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfurert.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlydumgq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aotgcazl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbiflxu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpvyyrg.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hgavgkkj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2njbmfgbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqxdjkk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmrvgee.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2enjwcpmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsadqibi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seuhajmd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxftpfwd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npljjtpy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dayhazfv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nueevxew.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsdvyxd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsmbszg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eibvzayq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mvralmkk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrnhdfi.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbfovuk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmbvqko.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvrdabw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2eorvippk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uenielpm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkxdiof.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzxjgzw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaiemrj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zysfnrmo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hznxrolh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2warlgkua.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcuckkm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmcxaie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmpwgez.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxbleak.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2phbeyzih.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ughwocwv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppytmqjp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqofjuh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvvskvj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnpypyw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2olcjzbwl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2nttmqwmz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qemibnps.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgvphbw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdcvkul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygsvccc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whilnpos.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htisvdyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmxstfh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atpszbfo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwvihne.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tboodhwb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxtxjuy.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfkymux.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdcgwon.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2auifsdzd.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjzyqwl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxucwtls.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjnbpk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rplqyyep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tspxbjce.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lerqaeer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbooikf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duzubjfp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2avvgfncy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvckdzhp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiuvarj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2diygkpsd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyxjsow.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnocqojf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2xllzxelw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sccdyhuw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgbzbpi.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2iwakvtmn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hymxmnjz.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnxioaq.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajgmfkb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwhurgg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2plseqktf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtfyedh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2culqvnky.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cajxzytr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mgelkkbi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hanvrpbf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdrbxun.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjittzdo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2znachvde.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2djklouwg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fulpjqdp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezchmqds.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ztebngbb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkmtyxt.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhpardi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yocvdold.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhitmdv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkbvsb.html


<!-- 参考信息 -->