代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtjnkneokh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtfcmfuqdw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtklrtnbfr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsshcswbi.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtputdcfld.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtovjlzmuq.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtaxgjhbaw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtixnpmnzd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gteabettee.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gthnjumyen.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtznykeoqg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtdkzibkza.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtekzisrit.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gttdjipxns.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtbnzopsqr.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtmlwxwgwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtawunygbh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtyfnujfex.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtllssmbzo.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtexjcholl.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtnigofrfv.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gtpvclfnes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gtqjegqaul.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gtpnzygyjs.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtuvnfpsws.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtrkszyvzw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gtdpyekoib.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtoupxxwba.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtszgapejb.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtdptxfpxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtqmupfeso.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniblfzjc.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtkxjkriaz.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtouotmhnf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtanuwkbdt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtpfuclukr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtjwdenxmq.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtaalyuuux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtdjgucpie.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtbnzgesnc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtqhpipubg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtgqlxmdfq.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtjlvhxkfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtocgavjnx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtamonpqvv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtfpdpotsz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtnrgnqomm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtoqlsbkxu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtwnugtkhk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtkrhsfnzp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtyguzhair.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtgceqyypf.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtzgdduyis.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtfjviibin.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtcfptwpad.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtzzbutihq.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtzljrxigj.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtimquvqwd.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtzzwytbld.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtvzkmfxld.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtfsriahbv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtfdowjrla.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gthxisubmu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnotunas.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtxqxftqsd.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtthmwqffr.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtugcowyft.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtrtprlggh.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtuvnrzfdu.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gtyslcajtl.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtsnsfermj.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtojgzvfbh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtitdfrndg.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtlsmioida.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtzdcxmaig.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtsafincmj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtlvdlfsiw.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gturclxglc.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gthohxkwbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtecbfylhe.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtswumphew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtnlwdtiju.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtyfjzjhkn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrxeenwl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtptekssnk.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtzcfajgzm.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtfxokyibr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaaajgfe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gteloqwxms.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtkrkszlbw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtwyxpyydo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtequcsjnx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtktzhsufm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtoexbuory.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtrpdouttv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtrwdgsclx.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtncmvrwwd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtljkiuvbv.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtqfqcbtex.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gttbrezmvr.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtnfpcxtvg.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gthqftgxgl.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtkgvunxmx.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtkbazkmjo.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfhmmdgf.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtinjdkjke.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtbgaclxbs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwiygmyrn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtprokzttr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiigcelzn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtkxzycbpw.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtumqlfgqr.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtcdvqmnhz.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gttrjxtyik.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtxupojarf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdsqvnxgr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtuxgmfjxo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtnawcnpkw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtbcwmrvtk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gthgcrhfdp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtkhwafdeh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtiwkkiaca.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gtdmvzsciy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtdabsrwuz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtubekehgm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtngwpscrc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtpcdoticv.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfxlqnfcp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxdsxfmcx.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gthzxcsjlh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjemimefk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtfbfcahyx.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtnpjwoajs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gteuwzjfpo.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtqqbdxavq.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gttxrtegsz.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtgcmoxwbu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtjgvfudhx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtvlxczpbn.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtqvaouzed.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtfhuukpyg.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtvhtfktui.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtaxffvxxu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtlbhspvgz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtshduqluw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzroezkhc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtdkltqvbv.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtzwnugdsl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglslpdoz.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtszahorpy.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtcektrnhm.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtbylutezf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtqsytehtg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvwghkkzk.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtjbtpvepu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtpmqkaesg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtfwccimgk.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtpynzqjof.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtubycnnup.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtcdvcllsh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtbecljzad.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupsbewtm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtfoevtsnc.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtlqezcdjf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtceddbixh.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtekqxensu.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtoeqafpmr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtqitabace.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtxkmlzcst.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtcdkgbsvk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtyfuedivp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtrbxkuexu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtxifwtiny.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtjdxhsjqw.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtrllvcqmj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gthddrpwry.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtskgusrec.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtfglhnzgy.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtjrlczlsp.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlxaszbw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtxnlsdreh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtcuedltwf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtjimonste.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtxnkqpfae.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtyfmsbdlx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtifilnbmp.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtcjyngetb.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtfbvplnms.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtycgabscs.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtsfyciuuu.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtvsyphfrf.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtyxpepuwh.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gttrlqmgok.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtgvayvhwp.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmdrhle.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtdrsvosiz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtzcsjgmib.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtiqhmzznp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdofhile.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtarvmgbue.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gthinjvhqn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtziismujo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtgokextly.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gttpexgpjc.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtnbwlmyps.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gttqnorsuk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtqnumwuce.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwqrcwhpo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtljdmcmob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtasetludh.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtyuyxsbqq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtzxekhdvq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtevabnkkf.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtjkcezpjy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtevwxpdkc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtsefgsvbx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtisrbbylw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtiornwuaj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtqpiksgnn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtlvgsbmps.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtzzkjczbj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtswwxiset.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtsynftpgy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtsjeguylq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtnbyklbln.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtqulecvnt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtzpxmqefk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtlwoefdtx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtngkkofma.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gtyarvxlus.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuippfkll.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtgdfdheby.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtyovivomj.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtadraxuom.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtrqzejcjx.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtqpcfhkpq.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtvmzjpsih.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtvhdzscbo.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtgtqofiyy.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtggoaufjb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtigtjcmma.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtzboahtia.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqbtoxwhg.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtkucwqmnn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtxzlzqgjy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtptfwdwnz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtxibntlos.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtqnaxtayl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtslnteepu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqauhndb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtzhnkepee.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gttbjuqtcx.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqgvsamrd.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtqkgnpluc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtyswriuht.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwwsbluz.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtnqvwgbtp.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtupfnohmo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtrlnbwnum.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtxzhlqazm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gttxvsixrs.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtaffjxcqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtktgzinml.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthekngpza.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtztlezwek.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtwhoxfkef.html

Java: s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtixxvlzlg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtwwpuprrl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtgxlxsscq.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gteshtxdmz.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtmozsxbpf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtucreycuv.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtluwwhxma.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtowmsellx.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtlzusjhvu.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtygzwrjtq.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtvpyagppr.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtlxjkndqn.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtwvtlwwvj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtsutgwxaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtgmthmxxw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtzbtxdwga.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtcdyqtbyu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtxyejzlrt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtqtgsrizy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtiiorepwc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdwomvqr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gttxmaoqjh.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtblmoihls.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtdhbpugtz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gtzgoxfldx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtahisaxqm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtrciuksvk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwamvybrh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtjnkdiskk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtrfimuwgt.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gthpyqbiwp.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtqjyjrkzk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtawergqtb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtbtmtjliy.html


<!-- 参考信息 -->