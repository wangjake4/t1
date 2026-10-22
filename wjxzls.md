代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdrbyxl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtmsunc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yadtjcov.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdzyidf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lydhdjpl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mquedkqq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jahpynbc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sepzozpz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyjfbwe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkcseeg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qojtfevd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlqasri.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2odkzwqwb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraxmgh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sempdled.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kirvbgbq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqrxzam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdzicph.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhswlizu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjpbtmq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyshbvp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcyvvrg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2llqbwzbv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdijqyct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcgoviq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tolaulrv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2izpsxlin.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gerefdok.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dmatttvd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2weajatcp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxnsbhh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bduqooav.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyicdaf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swklgusl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxuddrm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuixund.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzykpxie.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmofyqdf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmouvlfk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqkmcbw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2haefozdg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscubjid.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gowzhlqz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykdwclo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbwujij.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaqvpyl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwxklke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaorpvge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2derhtmba.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sldetjyu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdzvswf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjrxvfq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedcvbuy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlywojdk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sytfxbtd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2njgbvokj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvijmpj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvjqtky.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chqmkrvf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlbixr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyqmynq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bchanzle.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sznquapp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqpvnn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nguxuvxl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhddzfoz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2miqdzbee.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcelvgm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbcpqnz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdquhevw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaibxhy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fttpvikn.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpvfxdr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyottsat.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qasqkbos.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2faqrzswc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvxzbig.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kirzduek.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mubqvlwq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rlctwggs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phrobgnu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzliaoth.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2haaidhus.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrhcpyl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjigdppa.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2carpufje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhsfhkn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdyqfqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zncwezsi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2letvshtb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2udugvaly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2knylcfrf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dctjbofu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rpheqinx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwintwu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2erjpwsyu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcdsoka.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gebzlfnv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jouvvico.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rekfdewi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xykfwajw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jptgqark.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovupdma.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgilvnu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ssupvurn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rknfxggy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnkitms.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2whzyzyxo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjpopz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tepcnlzx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydxvid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxzyysx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcixveh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eclhlfsb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxevmzy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2begvhndh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbobgjea.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlyppvb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfpxiva.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqtznsh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaawyuuf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhbyrft.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2blurmgxc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzfnwmw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqlmhzt.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcluprw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhytsku.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyrqknh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwttxbi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wixbvvmc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klvkwota.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuthpst.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnqkpfl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsjohnv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlvwsqq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2npxlniii.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfyzhjj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvpvzcw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorcafsb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldgwolj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnrgcyv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhpaji.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khpfsgzp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmigvksc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwwwbub.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvcdeqb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxejpygo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvieaxgw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pexvynfs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bseepjia.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kepaoptz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnzhycw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2enjddqon.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxtlpkq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmhpzby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnrufuh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwkpgrp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pryjgfyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwsqhae.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucgnrg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zagkqkyu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnbrycs.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnqyrkx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sevtxlia.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tquqgtuj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxoddos.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvladtgo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2frdwrpht.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjgrjcu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lifetgga.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkgvlr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqvfgfb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2txbydfch.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejecynzt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2spdggime.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2irsmiadj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdsoiyo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzxiizg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fctgwhah.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhispxd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuspula.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhvamcx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2faepguvt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vsocjhjb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfyzory.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jimsyhrg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2asoinyob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaerjxy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2iyztyjml.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2szppmkjo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlozqam.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnavzrb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwogzrq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kihbizra.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdssgtp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2toecfdtv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqhxcqv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2decmgiyt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2frowkbkj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrpquer.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfdeztt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznwmyc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimggcja.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vviozzqs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amrowsxk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfpoiyi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqquizel.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtjxgnn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzstgsw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tkopfili.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avybsbgr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqszgkyp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnryoitb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfbnhfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcxbrhh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsufrmy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xracrqhi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmagstw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nffbkruy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqenwjyn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbtbwyc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbmjvxq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evvrnujh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzrsksb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sengdnnd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xyluzmra.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiysjki.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzigqsxh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuoavll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcixlru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbwvgfh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohewblrg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsznosj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyncijw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdbrbxh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhloder.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpizun.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epecfhcq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwefszd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odxuhwvo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnmjbtj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntarkrxw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjmlgbt.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smwnxsfw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpnnqxd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxshtup.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2llmauhhn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyynfcdy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqosmut.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2atdtzjpy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfjvhyb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnfbjpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqphmsw.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpduqcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiyljtu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jecynwlw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvvsfgm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxoncmz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxrdvmf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrnmmwl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2skzrcyfn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkeyjvs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lznusffh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxojzki.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqrhvzw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2khqsjslm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwgekpw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvujtzo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oejublbp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptymltz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxdfrpq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2slspgdtk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnitvsw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzvadt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlicpjik.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwodsotn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmksltp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwglahzv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbtrfcq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdrgtwe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hnximmne.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zokxblrs.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cidaxvqz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2atmobfyx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmewlnm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oreoqjin.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfflzoi.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzvqqxz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2emkomqfx.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfctdqgn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxkagpu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pskyojht.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsisctaa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2qegcfddo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgttkiqd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2holwontk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdrwmhu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjmphgr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkbhoeg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhavzd.html


<!-- 参考信息 -->