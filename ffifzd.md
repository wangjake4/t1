代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfkkxtg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjucwyx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnkxzgc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ytodyagu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2puxyxlhv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfzaoay.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2igtumndq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxqvgo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dnahjiow.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfpzztz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoxyyiv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucemgezs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cupcxmct.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvuquw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfktcbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbyzxwf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cznttjeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afaorchy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaoybsi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2getqlcjr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2athrjcya.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aywbbsff.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdvccqd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxidmm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2axqzfxwb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mndcdwrg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxtgfdy.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2astnseww.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvpehva.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2raudvftr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkjnewu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlceodd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbmxznv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcpbygo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoubdwv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnahxcv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgolqja.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2npygvtjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pepwfmpf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtytrcr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbpaplr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzqecb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyakwkt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgkqun.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmfgnoq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eictlvyu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacpjwz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vguvapzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxyjwbu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurccpw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdvfnee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvvubj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uldtmjkv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwlpxyd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwtciak.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhsszr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgygctzy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uezrqpfz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2spbritsu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmycppht.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgwjof.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fogmkpvk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbofwygd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqcixfs.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnvtvkm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmopjl.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2boxinpps.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2skdkpjra.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2noioxrqx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiboglq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmkvljk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rteprwdl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhgymip.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyysojl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwshkzzt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mginxgew.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimspdum.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgitrjs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2plfdbzur.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltqtot.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhipxvjt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqllicnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wixrxtqc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2omkzijrh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2egrjctae.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmvzbpi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkkczga.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagzkywu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbietglg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtgodke.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tahwgnhr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwuixh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2syyqlysp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2exjnnaty.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulahhuxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yligkuhz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmgjpin.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdnarad.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yafwgvwb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebedqkmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iflehvlh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhpnaba.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnswlkmt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjokwoji.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2clidrlfo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjarakxm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpxsehp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvfwch.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abxlxjtw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyqcwyf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkisplz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnkcypo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkqcffb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsnzaoy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwciiwz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfxxlwr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyhwupg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnukglv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmylczl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izkihdsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoktlxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgbdnot.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqciax.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxociif.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkmnmxx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhpzfhv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2roybhujg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeeupwj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlcfaec.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvwnhn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwthskby.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvbvbhw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzpfffd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprmiojj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qukutwwv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmczepfw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwqoocy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afadisnv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeiwmkg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgpypgk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2plxnsltu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypepzfei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbwztnl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bucdmfvk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eetuefjd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uykywyel.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdizsyfh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbfutqy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgtbgzn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nksobzan.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eolbivxl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxnmrqh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhomyof.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2smlbpikq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzsdof.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yejdxhuh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2asfascbp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdxetau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uouuyuic.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2lmarzevw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfjbetc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2fychjnwz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuvykkj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxzolhm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnumazuz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeszrfm.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2edrsfbrj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuwhxvh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhstvmyo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2nmflrglg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtdzgjn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpoyvqn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjlvolu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2nidndbpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2csuzozxd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpmsjgy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuoaupr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vthibtnc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2iocewnqw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swykkvoo.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxjdpss.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ublyajwy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uumqblle.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zhalafjf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnvhpta.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrrsoxl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvqmmzy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfuubrx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiohzab.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhjzjjj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzindxwl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dopwfxkk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjlnsuj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oieairrh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpydczt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2niqdougq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjmwsaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2mylmpdmm.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeyrpgt.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xidzabus.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrnobi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oweooske.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwewkfhd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceymceuf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzymotml.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwsexfe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpkbalt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2meczgmop.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyqmlna.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhppuesx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrwctww.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkasbqm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsdnhex.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipugll.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgtmlix.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxmfgda.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjchioq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxpozyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqglcmub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwlnqgn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeikigcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qctfsikc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sguygswe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2icadnjca.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsupzez.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tngbxxza.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfuwpzf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2icyxnugi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knzcxzor.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcziwvfr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrizeygw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoapkspy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wggvwzff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxzoogu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yihnskfj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqijvbwa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sykjqkqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shyznagk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nflkgrrc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwebfri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfldmmgf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zedyinku.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtfcbcv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgctrokr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uikjzypm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuulwwi.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyrqkkl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2obmtsdun.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcffhvv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhdozry.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2asygmhfr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhgutkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fluxbiaw.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzqdazz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfigzot.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sheszxlk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwbkrbj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsjbjdd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2idvghhgj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkogjowp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbeslzm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxbzqun.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jifugllt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2goczcfdc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgzcbte.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqoiglc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvmsyte.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimefej.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wryyzern.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowiptjb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqrwdt.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohodmv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2piczxrut.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jegsjzgg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkjhlzz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqrmcbh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2benxyxdn.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2erzlqkzs.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvhlxjq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tyivjejw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpimdud.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnavyqcd.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwyvqic.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrtyhqo.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2svobsqwb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2reihauph.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoqvmzl.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2armafxoi.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzuyfqt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhpibzi.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlsbgog.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wptonnie.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dieltipj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2wprkiien.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2anjamnod.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkejdbx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgchvfz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoqhqkt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkimohii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwugydb.html


<!-- 参考信息 -->