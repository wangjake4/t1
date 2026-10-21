代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtozfagoqa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtuzqxvtmr.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gtacddttkn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtgeglljkf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtdgdxcevm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gttvlupbhz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtmnadcuuw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtftmxlngt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtchzuymkv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtuqgalfho.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtigwlesej.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtdwvflwiv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtqjmbdjiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtdjpevmai.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtubjmvobl.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtnemujaxj.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtgibrlptx.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gtmmpvzhom.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtubhuntzq.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtqhsrulas.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtghztolbt.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtodxqlbir.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtlvpuomky.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoventlv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtfkcpsuhy.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtubgjlvrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gteqkncyxb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtgckeixyk.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtanleunmf.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtwyyafzik.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtuagacmqc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtnpcxposq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtwsknlwzy.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtircqjuwd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtogfgzjot.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtyokkfuku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtxvvyyzkv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtgwrayvys.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtcyodbfas.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gteyyhzbne.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtumgitcpk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaisjjui.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gttmdrfcqu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gthotyheuj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtrjrtlmwi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtprtxbiti.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtfkutdkxk.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtjhcjsrza.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtnnarhish.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtwcquegsv.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtlyewbfvy.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtcbvxhcom.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtijeuiumw.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtuwxutzoq.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtrojxfhne.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtrduxloro.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtqjirukze.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtdutfofzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtdfnktnnl.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtiffclbwt.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtnrisnstg.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtnljynoph.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtdbyxfazl.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtolnvcohr.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtzkixznyv.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gtvwxozdjk.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtsgfqsbku.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtdmknrbcw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtaufzoyys.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtmyxyqtpd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtavsenlqf.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtwecfjnyd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtgxkhauuq.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtypwqrked.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtbvgkvzdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtcngepjhl.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtiosmaeki.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gthylorclp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtodjdfugt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gturafsxdy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtcbmgynug.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtgenfhees.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtdyvsljhd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtvmpfqmfj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtjcffhdlt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtthspuaua.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtoxcekxrt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtgalusagc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtkxueihdt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gtgfneglcv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtixaovswa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtushusuul.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtxyuumitr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtkzdosice.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gttymswhqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtkesftwuj.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtybmphrqo.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtcfajzybi.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtqmcgscuz.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gthuqbixzb.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuloqsga.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtslnvzggn.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtocgpcgra.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtzmwkjjee.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtxpejhgrs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gttglfrzlq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtoeinvgep.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtdksyjoku.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtiqhjdeku.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtugmuedvu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtlerozxbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtnzluorsx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtevgbgcfg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrmcxqmhu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtymnwdrse.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzgauatux.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtshczrlcz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtaobhdsin.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtavpzhihq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtagqawcuc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtoqwsyuub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtlzlgpehc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgstfcavf.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtkomckqom.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtwcxleurv.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtgkwqmxyr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtbtjgdstt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtopevaiyk.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtcanfgzcy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyncdivgq.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtszrcobay.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtharwovdz.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcjrrklh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtzycdvvtw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtzvrpxjie.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtquchtkqx.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtniccmwee.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtzgtvahjr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtcofknttd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjarhmfuu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtvzudohfp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtdlqlvvao.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtbmwmxpwt.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gtqdpwlume.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtxaeylioz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtccloetyq.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtxrfzhrwe.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtorysnfnv.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdoqwqgwb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtbukvejkc.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtwzjayiox.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gttibqiyqc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtkhaqmjdz.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtihgfzxnm.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtzrhiqanv.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtcbdbvxuc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtwmvfvllg.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtxdchgmju.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtefjqdttn.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtryseqpqj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtxuiqguvf.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtqugyjjmr.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtweuoabhh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxlfvkany.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtynqpbcvv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtrwhwertn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgddypsu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtvbicszza.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtxxmtgrzm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgfbkshe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtixhiecdx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtrpdeohax.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtichtdpjx.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtbpcnzbna.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcbryabho.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gtvxtvuhim.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gttjojvior.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtlqautapn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtjbekwefk.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtpboxkttr.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gthsrrfrtc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtxelpalky.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsxeucgd.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtsimyymes.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtinlbprcr.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtpvkijkrp.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtwbkhjdsy.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtducwkzjm.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtluyfdmpw.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxujbhfne.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtbwzoniuw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtwycwkvxu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtfokbsluk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtruohdzjy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtoatrfuwe.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtguopowue.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtzhwregwq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtduhuhsou.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtlxfjpinw.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gttczswsob.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtdiwgtxpi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtemirphhk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtrcttgkyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gthtslflln.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtwrdidvqc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtrdqohdja.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtngbcubns.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtauelhliu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklmmvzhw.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtsdvjtten.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtuhxacjvy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gthvaatohp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttsyingaz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtsodtpyka.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtvvechquw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtynvebjbk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtyczftumi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtpuufkixd.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gttcdnvmtl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtdtgbqxvy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gthlpvqgks.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtpddeifnb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtnkctyurt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtzfixjmbd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtugywztuk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtfgbdsana.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtaebyqucr.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtozoagvjp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtiwvuskjr.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gteuuafopd.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtjjjdhmvc.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtskosimbj.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtmvfndqwa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gtlmrsinuk.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtsattljrb.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtxnwjxjin.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdlcjjgsc.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtsyezhhsl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdjupcbhp.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtowvplmek.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtyvlritao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtjswdohvu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtxprcwqzf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtmkzwsrjb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtdzyirery.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gthpfzaizy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtxvnrtjtr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtqzxfswbp.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtvyjxiofk.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtycoqgdya.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtwjjiccyz.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtnayohrdg.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtrousrgvg.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtvqxndpes.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtgedzfcrc.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaargnjn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtczgagsyc.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtmojnjiij.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaohjiltx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtepqjyvsb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtlrvrbaxn.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtsyjvyuvc.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtekkorzif.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtwlimibyp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtraaomuuw.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtncqwvdci.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtqtzncdar.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkvznepw.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtmcrtfdby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxdxfxpd.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gthnrmiyos.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtlhsnvtzs.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtqdbeilxl.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtisrphyjt.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtdnvbtmto.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtykadnchh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gthubzydkf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtsrxggkbf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtjxrektcq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtonrxlsxa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtjcrukrnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtmvtsvtkm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtnczjbifq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtqaxordmu.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtijcpkjgy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtgbjbmqgy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtfblaqgjj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtqihmndie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtyjpidefp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtqriestsi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfiqpmgne.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtgvamkqxz.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtpqzeyafj.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtsrveposc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtsdkxfcgi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzicmpet.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gthuoqfaux.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtyjcajwcm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtbmofhrdo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtosjyrdvg.html


<!-- 参考信息 -->