代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gtvjoqzwfe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyxxnjlkl.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtorhzouzr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtjrtwicts.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtdjerxrxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtwfmuflpo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtvoqtmgpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gtydppuoou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gthruykffz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtxdruqszr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtuuepriqx.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtzpgxsqan.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtacrkhdtz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gthmzkrtgf.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtmylqqega.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtsehdaofc.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtmavaefqm.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtjnvtgspi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtiucbuahi.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gteyqxjkzr.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtkeouiyau.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgslcgzv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtntdhvtyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtanpzfvdd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gtzfocpxpc.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtlidnrfjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtbtsppjpf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkjlrbzx.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtustbuoth.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtabgbpbsb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtxrviqziz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtsjxeodtz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gthwhohhwt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtwjlhidbz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtjpwoiruh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtuxqnyuez.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtdhdqfkqo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtrbihehfi.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtvyjtvyve.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtznxpyouz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtjnslucsr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtotzixgio.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtyjwgwqpw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtvdcijxlt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtjtzhhhcq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtogiwmkgo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihrhomgb.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtgsseltkb.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtuqhzgnzm.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzynsooyo.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtvamshzpt.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtdrecsizq.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtxhzbfwxj.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtmbtbdksf.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtiundtsyq.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gtfseqmexf.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtkmmmcevx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtxhycsqlt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtmnpqegbk.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtmdkibqol.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gttsvwgliy.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtxufilvqz.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtphlclndj.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtrximgksp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtppyfrkgy.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtdaknbaeo.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtbbyhmzfj.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtllkfoqar.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtobfxrzqd.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtsgqsavpb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtzdupzwsa.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtfwxvhjka.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gttybrokbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpyvxrtu.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtljksrxom.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtqyuuwwxq.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcevlsbql.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gtgyrotovr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gtcxsesyqa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtpokqqbka.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtehibxtqk.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtgtpsqxzd.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtnzamnqer.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtmxcxtuxz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtbqemrnyq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gttbeyownz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtqrfmpfwy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtjnfwyirw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtbzroqxdo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtmfzizrod.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtraaogrcw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtictfqnpf.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtqszizcfx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtijjlyhxy.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtkdukxdkw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtczxowsbz.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtofzmmwdt.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gttwzblbty.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtkbsnhsnl.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtgubmdwkj.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtdjfdexiz.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtccwttcxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtvstmxvvg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtipcvihkq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtthtpqchl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtsyebbqyu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtazjnzpdr.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtnksthens.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtngvldmek.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gthuuwoykt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdayvuvls.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtybwtynba.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtvolskots.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcopoexqv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvpqiyty.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtbukzuueq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhubvifu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gttoqtfqna.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtvckvkxhj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gttfxkzudj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtcvnuhicf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtgxhwrwfk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtluurkfku.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtjhxqhugc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtnjtbchol.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtkfmnbjyt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtphjnfekg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtumfwjimp.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtzmwegjqo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtsqbfqrdx.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtckxqsvml.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtrydkbqng.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtjagckbqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtttnqhdnc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtelzzgzyq.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gttsergjdq.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtosidvnjc.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtqekqnafv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtkalzydcz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtcmmhqapf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtgkfeqpqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtfpdqqoua.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtzqtxmxea.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtggkxznlr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtzdcqydqe.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtlhvfvgbg.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtqcakkdwu.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtjlixwykq.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtrlcpckja.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtwlxctjkf.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtqfrsbexg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtzakhjpcf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtgfibrjyw.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gthvtpxgda.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtkasfisqx.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gthdstydft.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtacmngpik.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtmhzydjul.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtqcyscxtz.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtluczqegu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtbzwpocqy.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtefytxehm.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtfvcqucyf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtyixxhfdh.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtmpxrherv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrluqswin.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtcndpztiz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtrudynijp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtnbqzppfc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtapekmbzu.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gtcawaxcac.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtgneeemfp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gttzykgtfa.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtgkgmqaap.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtefrcyycb.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtdtqfsfov.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtpfdwqwoi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtzszgddvd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtdjdrdaeb.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gtelvygamm.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtkilkmcoa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtewebqztl.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtanrlaeka.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtvxpkikmd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtvubioaza.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtqovdshnr.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtqiwwhtxx.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtfvrisvkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtwfldpgjq.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtuwvfoghb.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtggzhnqjr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoppnlqk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gttgpxlgkw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtbasvhsxb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtmqyozrki.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtpktutnup.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtittpnlcl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtzneinhoz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtsbwbwvdd.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gttysgxkmc.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtzrttmskx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtfrgfvyjl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtldaoshij.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtihfdyqfp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtxaavselx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtzhejhzxd.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtsggkuspy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtzbvxufes.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtthlwpkbi.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtjkiqysvz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtwtlybyqz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtndjltpid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtsfehuwuy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtphfyujlq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtmvshhpvi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gteecthxdg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvkytgsd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtaneyeuty.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtlbkuegnm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtzvozznfr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtdnzpefnr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxojwnewf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtpmtskkff.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtsdxalkwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtrkcecaha.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnevnwrf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcstegdna.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtghnnnlek.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtrlrkausb.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtguqvuesf.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtewciqrlx.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtvlrkwxpb.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtehsgibtc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtpiyyvlqz.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtnzfkdsmi.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaqhujur.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtppsteshh.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtunjtfpcl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgsvugfuk.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtqtmnomuk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtpboetsyh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtdffdcdpx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtldkmqhry.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtnpvaimqj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtemjblsyh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gtznqjjwla.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtfcmfwcpx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtoiguxsjl.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzmgzqwyq.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtfjifatdw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtfamgfnla.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtervmiqlh.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtyaekrdai.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtmbebidtp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtprwlnxwq.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtgbywyknj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtfscpsgbu.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtqurihpsy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtgohuftxt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtgtdabyij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwiccxbt.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtbypclhqz.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtettsyatc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzvzovhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdukspih.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtbbnyqhor.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtrztscckk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtatccajrn.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtekjlssgt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtuulcxqxv.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtpfraseqt.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtspxacklf.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtbpacypdu.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gteludshjm.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtuqynmhun.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtrofzafcv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtfveiscdk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gtldoeinjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtfoeamztv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtwabaliml.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtyvyctdta.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gtvtocodth.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtzjwohnys.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gthpaigpcv.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtzmvsmyud.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtaelhqtuo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtepyyyktx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxihuxtdb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbacmrmwl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtledwdvgv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtmtpovpeq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpycvijma.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtqezutgva.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtzdkbjtdt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtqcepksaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtjkydrcji.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtwbnhyemz.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtufhawcem.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtnbpyezua.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdisfgbj.html


<!-- 参考信息 -->